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
