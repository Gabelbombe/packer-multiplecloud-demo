#### Proof of concept for hybrid Packer build-outs

##### Intro

##### Requirements

There is some required software needed to run the following:
Brew install the following
```
$ [ ! -d ~/Applications ] && mkdir -p ~/Applications
$ brew cask install virtualbox vagrant vagrant-manager --appdir=~/Applications
$ brew tap homebrew/binary
$ brew install packer
```

 * [VMWare Fusion](http://www.vmware.com/go/try-fusionpro-en)
 * [Parallels Desktop](http://buy.parallels.com/329/pl/67432930-eXRF2V6vmrxj02kCvVzZ-1-1-1)
 * [Parallels Virtualization SDK](http://www.parallels.com/download/pvsdk/)

 ###### Notice

 After having __several major issues__ with installing VMWare Fusion on OSX I recommend using this as the _preferred_ installation method from here out.

 ```shell
   ## Install Brew
   $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

   ## Install Cask for Brew
   $ brew install caskroom/cask/brew-cask

   ## Install Fusion
   $ brew cask install --appdir=~/Applications vmware-fusion

   ## Validate Fusion App
   $ open "/Applications/VMware Fusion.app"

 ```

##### Utilization

##### To do
