# Tmux - Multiple Termianls

```shell
sudo apt install tmux
```

## What is Tmux
Tmux is a helpful application which allows for multiple terminal sessions to be accessed simultaneously within a single window as shown in the below image. 
![Tmux multi-terminal](assets/images/tmux-resized-multi.png)


### Sessions
```shell
terminal# tmux new -s <insert name> This will create a named session with the defined name. 


```


# Screen - Multiple terminals

```shell
sudo apt install screen
```

Screen is used to create multiple virtual terminal session. The screen allows us to resume or start a session. 

```shell
terminal:~$ screen -S <insertname> # This creates 

terminal:~$ screen ls # Shows all sessions

terminal:~$ screen -r <insert_name_of_session> # This rettaches to a desired session
``` 

Detattch screen: `CTRL + A + D`


### Resources: 
1. [Tmux cheatsheet](https://tmuxcheatsheet.com/)
2. [Screen Cheat sheet](https://opensource.com/sites/default/files/gated-content/osdc_cheatsheet-screen-2021.4.14.pdf)

