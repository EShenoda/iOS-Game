
# <p align="center">iOS Game </p>

<br>

<h2 align="center">Card Matching Game</h3>

<p align="center"> <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://developer.apple.com/assets/elements/icons/xcode-12/xcode-12-96x96_2x.png" width="42" height="42"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a>  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;</a>  <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" width="40" height="40"/> </a> </p>

__Main concepts__: 

* Core Data
* UITapGestureRecognizers
* Stack Views
* Button Collections
* Custom HeaderFooterViews
* Custom TableView Cells
* Size Classes for iPhone & iPad
* Swift Timers
* User Interface Idiom
* AVAudioPlayer
* Custom Animation


__Extra functionality to add to the user experience__:


AudioPlayer


```Swift
// Audio Player
func playSound(sound: String, type: String = "mp3") {
        if let path = Bundle.main.path(forResource: sound, ofType: type) {
            do {
                let url = URL(fileURLWithPath: path)
                audioPlayer = try AVAudioPlayer(contentsOf: url)
                audioPlayer?.play()
            } catch {
                print("ERROR")
            }
        }
    }
```

<br>
<br>

<h2 align="center">** Please allow a few minutes for GIFs to load ** <br> Thank you so much</h2>

<br>
<br>

__Load Game Animation__

<p align="center">
  <img src= "Images/Loading.gif" height= 350>
</p>



___


__Animations for pulsating Start / Stop button__

__Flashing Colors__

<p align="center">
  <img src= "Images/Button.gif" height=350>
</p>

<p align="center">
  <img src= "Images/iPad.gif" height=350>
</p>


___



__Card Shake Animation__

<p align="center">
  <img src="Images/Shake.gif" height=350>
</p>


___


__Custom Segue Transition__

<p align="center">
  <img src="Images/Segue.gif" height=350>
</p>


___

__Layout Changes__

<p align="center">
  <img src="Images/Layout.gif" height=350>
</p>


___


__iPad: Add Progress Bar & 10 Extra Cards__


<p align="center">
  <img src= "Images/ProgressBar.gif" height=350>
</p>

<br>
<br>




## [Click Here to View More iOS Illustrations](https://github.com/EShenoda/iOS-Illustrations)

<br>

##  Copyright
Private Repo for EmilShenodaDev@gmail.com

All rights reserved: EmilShenoda@FullSailUniversity

## Contact
Created by [Emil Shenoda](mailto:EmilShenodaDev@gmail.com) - feel free to contact me!



