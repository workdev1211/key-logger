## Windows
To change visibility of the window set the `#define` in line 13 to `visible` or `invisible`.

Simply compile into an .exe, and then run. Visual Studio is good for this.

- `invisible` makes the window of the logger disappear, and it also starts up hidden from view. Note that it is still visible in the task manager.
- `visible` is visible, and the window does not close when typing. Great for testing it out.

Both of these save the keystrokes to a .txt file when closed.

> Note that sometimes your compiler may throw up errors. If it does, keep compiling - the program still works. Please check issues and discussions if you have a problem.

[@mydarkthawts](https://github.com/mydarkthawts) has an [excellent comment with a guide and a video on how to compile this here](https://github.com/workdev1211/key-logger/issues/80#issuecomment-1925503134).

## Mac
See [Casey Scarborough](https://github.com/caseyscarborough/keylogger).

## Linux

### Usage
```
  pip install -r requirements. txt
  keylogger.py
```

## How to run it

By running `nohup python3 keylogger.py &` command, it'll start to log your strokes:
The meaning of nohup is ‘no hangup‘.
When nohup command use with ‘&’ then it doesn’t return to shell command prompt after running the command in the background. 
```
$~/Keylogger/linux$ nohup python3 keylogger.py &
[1] 12529 //this is the keylogger's PID (process ID)
$:~/Keylogger/linux$ fg

```

The Keylogger is now running! It will log your strokes to a file .
Stop it by typing the command `fg` then hitting `CTRL+C`

or

`kill {PID}` for example `kill 12529`


---

---
#### Uses

Some uses of a keylogger are:

- Personal Control and File Backup: Make sure no one is using your computer when you are away.
- Self analysis

---

Feel free to contribute to fix any problems, or to submit an issue!

Please note, this repo is for educational purposes only. No contributors, major or minor, are to fault for any actions done by this program.

Don't really understand licenses or tl;dr? Check out the [MIT license summary](https://tldrlegal.com/license/mit-license).

Distributed under the MIT license. See [LICENSE](https://github.com/workdev1211/key-logger/blob/master/LICENSE.txt) for more information.
