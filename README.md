# Musicplayer - Redefine the Music Player
**A pretty UI & UX Music Player**

## Features
* Dark Theme Style with wallpaper as background
* Single activity, all fragments architecture with fancy animation
* Play the sample/preview of a song, audio visualizer progress bar
* Play Controller is able to be opened everywhere
* Large artist image loading, and can be used as background
* View lyrics, view song details
* Metadata editor
* Learn your hobby, automatically create new playlist
* etc

### Installing
The app will be available in Google Play Store soon.
```
Comming soon
```
### APK
Download apk file here [Music Player](https://github.com/mikrodinet/musicplayer/raw/master/app/src/release/music.apk)


# macOs

Download
```
# Create a folder
$ mkdir actions-runner && cd actions-runner# Download the latest runner package
$ curl -o actions-runner-osx-x64-2.304.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.304.0/actions-runner-osx-x64-2.304.0.tar.gz# Optional: Validate the hash
$ echo "26dddab8eafc193bb8b27afc5844ff3a6f789a655aca5bf79b018493963681a7  actions-runner-osx-x64-2.304.0.tar.gz" | shasum -a 256 -c# Extract the installer
$ tar xzf ./actions-runner-osx-x64-2.304.0.tar.gz
```
Configure
```
# Create the runner and start the configuration experience
$ ./config.sh --url https://github.com/mikrodinet/musicplayer --token A3WZ3XVQXIPQPRMEJRM3DPLEMDZCA# Last step, run it!
$ ./run.sh
```
Using your self-hosted runner
```
# Use this YAML in your workflow file for each job
runs-on: self-hosted
```

# Linux

Download
```
# Create a folder
$ mkdir actions-runner && cd actions-runner# Download the latest runner package
$ curl -o actions-runner-linux-x64-2.304.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.304.0/actions-runner-linux-x64-2.304.0.tar.gz# Optional: Validate the hash
$ echo "292e8770bdeafca135c2c06cd5426f9dda49a775568f45fcc25cc2b576afc12f  actions-runner-linux-x64-2.304.0.tar.gz" | shasum -a 256 -c# Extract the installer
$ tar xzf ./actions-runner-linux-x64-2.304.0.tar.gz
```
Configure
```
# Create the runner and start the configuration experience
$ ./config.sh --url https://github.com/mikrodinet/musicplayer --token A3WZ3XRWA4XMQAYWQSQV6E3EMD4L4# Last step, run it!
$ ./run.sh
```
Using your self-hosted runner
```
# Use this YAML in your workflow file for each job
runs-on: self-hosted
```

# Windows

Download
We recommend configuring the runner under "\actions-runner". This will help avoid issues related to service identity folder permissions and long path restrictions on Windows.
```
# Create a folder under the drive root
$ mkdir actions-runner; cd actions-runner# Download the latest runner package
$ Invoke-WebRequest -Uri https://github.com/actions/runner/releases/download/v2.304.0/actions-runner-win-x64-2.304.0.zip -OutFile actions-runner-win-x64-2.304.0.zip# Optional: Validate the hash
$ if((Get-FileHash -Path actions-runner-win-x64-2.304.0.zip -Algorithm SHA256).Hash.ToUpper() -ne 'fbbddd2f94b195dde46aa6028acfe873351964c502aa9f29bb64e529b789500b'.ToUpper()){ throw 'Computed checksum did not match' }# Extract the installer
$ Add-Type -AssemblyName System.IO.Compression.FileSystem ; [System.IO.Compression.ZipFile]::ExtractToDirectory("$PWD/actions-runner-win-x64-2.304.0.zip", "$PWD")
```
Configure
```
# Create the runner and start the configuration experience
$ ./config.cmd --url https://github.com/mikrodinet/musicplayer --token A3WZ3XRWA4XMQAYWQSQV6E3EMD4L4# Run it!
$ ./run.cmd
```
Using your self-hosted runner
```
# Use this YAML in your workflow file for each job
runs-on: self-hosted
```


## Screenshots
</br>
<div align="center">
   <table align="center" border="0" >
  <tr>
    <td>
<img width="360"
src="https://user-images.githubusercontent.com/33343210/61610738-2c46aa80-ac84-11e9-80fa-bbe8c6d4119a.png"/>
       <td><img width="360"
src="https://user-images.githubusercontent.com/33343210/61610968-c3abfd80-ac84-11e9-9c8a-7ac5c9e257ff.jpg"/>
    </td>
     <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61610657-edb0f000-ac83-11e9-8b89-eb205d8ac518.png"/></td>
  </table>
  </div>
</br>
<div align="center">
  <table align="center" border="0" >
  <tr>
    <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61611561-45e8f180-ac86-11e9-932a-d0cbcd388048.png"/></td>
     <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61611407-e38ff100-ac85-11e9-8b70-f083436cf3d4.png"/></td>
     <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61611355-c6f3b900-ac85-11e9-9b0c-c3c3a4734474.png"/></td>
  </tr>
</table>
  </div>
</br>
<div align="center">
  <table align="center" border="0" >
  <tr>
    <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61610594-c3f7c900-ac83-11e9-8ccf-1a6d989631d2.png"/></td>
    <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61611516-2d78d700-ac86-11e9-9187-c53e91a2b891.png"/></td>
     <td> <img width="360"
src="https://user-images.githubusercontent.com/33343210/61764970-4eb40180-ae05-11e9-9903-241fa144582b.png"/></td>
  </tr>
</table>
  </div>
</br>

## Authors

* **Le Dinh Trung (ldt)** - *Initial work* - [Mikrodinet](https://github.com/Mikrodinet)
* Officil Website [MIKRODINET](htttps://www.mikrodinet.eu.org)


### License

* This project is licensed under The GNU General Public License v3.0 - see the [LICENSE.md](/LICENSE) file for details

### Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc

