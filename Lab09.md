## Lab 09

- Name: Isabella Livingston
- Email: livingston.70@wright.edu

## Part 1 Answers

- Make sure infinity is in your Lab09 folder in GitHub

## Part 2 Answers

1. Getting started
   - Command to find the PID: ps ax
   - PID of "Terminal A": 121365 121052 118067 6437932187 32136 32069 32066 31458 30955 30804 30662 30460 29496 28360 27712 25876 25706 25566 24987 24107 24011 24008 23994 23384 23124 22856 21449 21345 21342 20937 20486 17392 15630 15276 13586 13091 13088 12809 11887 11884 11564 11505 11384 11084 10827 9708 9681 9638 9635 9368 9270 9267 7831 7828 7727 7595 7592 7589 7297 7180 7177 6667 6346 5953 5796 3989 3731 3487 3484 3133 3130 2789 2205 2195 2192 2190 2179 2173 2170 1967 1965 1384 1381 1284
   - PID of "Terminal B": 32187 32136 32069 32066 31458 30955 30804 30662 30460 29496 28360 27712 25876 25706 25566 24987 24107 24011 24008 23994 23384 23124 22856 21449 21345 21342 20937 20486 20330 17392 15630 15276 13586 13091 13088 12809 12695 11887 11884 11564 11505 11384 10853 10852 10827 9708 9681 9638 9635 9368 9270 9267 8400 8396 7831 7828 7727 7595 7592 7589 7297 7180 7177 6667 6346 5953 5796 3989 3731 3487 3484 3133 3130 2789 2205 2195 2192 2190 2179 2173 2170 1967 1965 1384 1381 1284
2. Using `./` to run `infinity` in Terminal B
   - PID of script: ps ax | grep infinity 
   - Command to kill script: kill 122952
   - Effects of running the script: Printed out "Terminated" to terminal
3. Using `source` to run `infinity` in Terminal B
   - PID of script: 118067
   - Command to kill the script: kill -9 118067
   - Effects of killing the script: Terminated Bash
4. Running `infinity` as a background job in Terminal B
   - Command to run script in background: ./infinity &
   - Job ID of script: 1
   - PID of script: 125197
   - Command to kill script via job id: kill 125197
   - Effects of exiting terminal: The background job is terminated since it does not show up when using "jobs"
5. Run `infinity` in a `screen` or `tmux` session 
   - Command(s) to run `infinity` in a screen session: screen >> ./infinity
   - Detach from `screen` / `tmux` session: Ctrl A and D
   - Command to show `screen` / `tmux` sessions: pgrep screen
   - Effects of exiting terminal: Screen is still running
   - Command / steps to kill the `screen` / `tmux` session: kill 126422

## Part 3 Answers

1. git branch updates
2. git checkout updates
3. Added "# Hellooooooo" to infinity script
4. git push --set-upstream origin updates
5. git checkout main
6. git merge updates
7.
8.
9. Confirmed?
10.
