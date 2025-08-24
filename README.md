# songs
Songs for Encore

## Guidelines
> [!WARNING]
> Songs that are officially in *active plastic instrument games* will not be accepted
> Any songs from games that no longer have developer support can be added if they aren't in a active game (such as Fortnite Festival)
> Songs from YARG as fine as long no assets are taken from YARG specifically.
> Encore does NOT endorse piracy.

- **If your chart is uses the legacy json system from before Encore v0.1.3, please update your `info.json` to the new format. <br> You can read about it here: [CHARTS.md](https://github.com/Encore-Developers/Encore/blob/main/CHARTS.md)**

- **Once Encore 0.2.0 releases - Unless your song only uses PAD instruments, it is *highly* suggested to format your songs in INI, so that they can be played in multiple different games. <br> Otherwise, songs that use only PAD but are in INI won't be accepted because no other games support PAD as of writing.**
  
- **Songs must have all instruments of a song charted, excluding Keys, Rhythm, 6-Fret and Pro/Elite Charts. Likewise, all Classic Instruments must have a PAD counterpart. <br> Exceptions are made if the song is notably long or the chart originates from a game that doesn't have a particular instrument, such as the Harmonix Guitar Heros.**
  
- **PAD Charts must follow proper charting guidelines. See more here: [Encore PAD Charting](https://docs.google.com/document/d/1Xqi_IR-FYI-PplGYDTO0HWMW_VGBshPFfFgZkps1tRk/edit?usp=sharing)**

## Publishing your charts
To publish a song, the chart must go under review and be validated.
In order to publish a song, follow these steps:

- Fork the `songs` repository

    Create a fork of this repository by clicking on the **Fork** button. *Don't clone it!*

    ![fork](images/fork.png)

- Make a new branch
    Inside your new fork, click on the button that says **Main**, after that click on **View All Branches** in the dropdown menu. <br>
    
    ![branches](images/selectbranch.png)
  
    After you select View All Branches, click on the green button that says **New Branch** then type in the name of your branch, preferably your song name. <br> This process allows you to more easily create pull requests for multiple songs.
  
- Archive your song
    
    Package the `song.ini`/`info.json`, audio file(s), and album art into a folder. After, create a ***zip*** archive of the folder.

    The limit for uploading files is **100 MB**, as set by GitHub. However, we recommend your zip to be under **50 MB**.

    **Only zip files are accepted. <br> Make sure to add all your files within a folder inside the archive's root.**

- Upload the song

    To upload your song as a **zip** archive, press the **Add File** button, located besides the green **Code** button.

    ![add-file](images/add-file.png)

    After, click on the **Upload files** button that shows up in the dropdown menu.

    ![add-new-file](images/add-new-file.png)

    Now, drag your **zip** song to the page.

    After your **zip** is done uploading, it will show up below the space to drag.

    ![fileupload](images/fileupload.png)

    After, click on **Commit changes** to confirm the song upload. Make sure you are committing to the **main** branch.

    *If you'd like to add multiple charts, you should create multiple branches and commit each chart to each branch, then create multiple pull requests, so this process can stay organized.*

- Create the pull request

    Click on the **Contribute** button below **Add file**. After that, click on **Open pull request**

    Under **Add a title**, specify your song name.

    Under **Add a description**, follow the instructions on the PR template.

    When you are done, click on **Create pull request**.

- Wait for approval

    Your chart will be approved after it is verified. If there are any issues, the reviewers will comment on your PR about them.

    When your chart is verified and the pull request is merged, you will be able to see it in [FNLookup](https://fnlookup.github.io/encore/), where it will be given an ID.
  
## Resources for charting

- [Encore PAD Charting](https://docs.google.com/document/d/1Xqi_IR-FYI-PplGYDTO0HWMW_VGBshPFfFgZkps1tRk/edit?usp=sharing)

- [Multi-Game INI REAPER Template](https://cdn.discordapp.com/attachments/1239998132427948163/1389545032503136317/Multi-Game_Chart_Template.rpp?ex=68854ee8&is=6883fd68&hm=0cd9881212619a3932aa66a79994a5be55802ca5eed76a534a7b7a0948d1e52d&)

- [Legacy JSON Encore REAPER Template](https://github.com/Encore-Developers/songs/raw/main/images/Encore%20Template.zip)

- [Download REAPER](https://www.reaper.fm/download.php)

- [Classic Instrument Guide for REAPER](https://docs.google.com/document/d/1b7KcHJ5uX-jcAjeRTStJRxcEvZ5ohYNOeVvezG03vwA/edit#heading=h.u8vd9w9b6n0y)

- [Original Chart Previewer](https://github.com/NarrikSynthfox/EncorePreviewer)
- [Fork of the Chart Previewer with INI and KEYS Support](https://github.com/WowItsOnlyConnor/EncorePreviewerINI)

- [Pro Vocals Previewer](https://github.com/tposejank/EncoreVocalPreview)
