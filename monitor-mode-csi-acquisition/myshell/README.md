```
# move the foler "myshell" to linux-80211n-csitool-supplementary
# for receiver
sudo -s
./run_monitor.sh setup # run only once
./run_monitor.sh

# for transmitter
sudo -s
./run_injection.sh setup
./run_injection.sh