# jay-utility

git pull all
alias gpall='find ~/$ROS2_WS/src -type d -name .git -exec sh -c "cd \"{}\"/../ && pwd && git fetch -p && git branch && git pull && git remote prune origin" \;'
alias gdellocal='find ~/$ROS2_WS/src -type d -name .git -exec sh -c "cd \"{}\"/../ && pwd && git branch | grep -v '^*' | xargs git branch -D && git remote prune origin" \;'
alias rosdep_install='cd ~robotis/$ROS2_WS && rosdep install --from-paths src --ignore-src -r -y --os=ubuntu:noble'

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
