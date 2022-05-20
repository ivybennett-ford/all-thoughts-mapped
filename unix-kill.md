# [b0rx wizard zines](https://questions.wizardzines.com/signals.html)
### `kill`

counterintuitively, you can use `kill` to send *any* signal, not just signals which kill the process. For example:

$ kill -STOP 1234

will send a `SIGSTOP` signal to PID 1234. The system call that's used to send signals is also called `kill`.

#signals #linux