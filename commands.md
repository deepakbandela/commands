Ubuntu commands
Download file with redirections
curl -O -L -J https://example.com/url



Java
Update Java alrenatives
Add new alternative
sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-15.0.2/bin/java 1

View Alternatives
sudo update-alternatives --config java

Install deb
sudo apt install -f /debfilepath.deb 
-f for install dependencies


Git
Adding executable permission
git update-index --skip-worktree --chmod=+x foo.sh


Git projects running tasks
include 'projA'
include 'projB'
include 'other/projC'
include 'other/projD'

gradle projA:helloTask
gradle :other/projC:hello
