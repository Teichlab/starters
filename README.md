## New starter checklist

First off, hello and welcome to Teichlab! Below you'll find a list of things that are good to set up as a new person in the lab. 

**Getting started:**
* Await an invitation email to Slack. Once you register, you'll see a message from Slackbot. Interact with the bot and select Teichlab once prompted for a team to join.
* Determine your admin person to help get you set up. Find the highest person on this list who is not on holiday as per Slack:
    * Krzysztof Polanski (kp9)
    * Simon Koplev (sk29)
    * Shuang Li (sl37)
* Make a GitHub account if you don't have one. Please ensure that you fill in your full name in the account details for ease of identification. Write your admin person on Slack with the following:
    * A quick introduction
    * Your GitHub user name
    * Whether your Sanger computer is Mac or Windows
    * Your Sanger computer's machine number (written on the red sticker on the lid)
        * *The admin-side instructions are [here](https://github.com/Teichlab/starters-admin) in case they're needed*
* This will result in some emails going out with you on CC. Once the emails resolve, follow the [quick start guide](https://github.com/Teichlab/scripts/tree/main/data_processing/quickstart) to get set up computationally. If anything goes wrong, contact your admin person for assistance.

**Useful resources:**
* Your Sanger machine should come with GlobalProtect, a VPN for comfortable off-site working. On Macs, look for a little globe icon in the menu bar at the top of the screen. Click it and log in via Okta.
* The desk booking system is [here](https://sanger.officespacesoftware.com/visual-directory/floors/439). The link should take you to Morgan 2, where you're likely to encounter a lot of other Teichlab people in the open-plan office.
* A master post of bus-related information (links to timetables, step by step booking app guide) is available [here](https://fred.wellcomegenomecampus.org/Interact/Pages/Content/Document.aspx?id=2075).
* The main group meeting happens Mondays 2-3pm in C3-03 in the Sulston building. Wet and dry meetings happen on alternating Fridays 9:30-10:30 am in C3-03 as well. There are a number of other project-related meetings taking place, with a master spreadsheet [here](https://docs.google.com/spreadsheets/d/1MQZBzP1h9KcrBkpvOS1ay6ugQwfHBETs/edit#gid=2127558975).

**More specialised:**
* Email servicedesk to enrol for a farm course, which will allow cluster job submission once completed.
* Set up [rclone](https://cellgeni.readthedocs.io/en/latest/rclone.html) for Google Drive communication. Please avoid putting any sequence data (FASTQ/BAM/CRAM being the most common) there due to ethics.
* JupyterHub offers [documentation](https://cellgeni.readthedocs.io/en/latest/jupyterhub.html) in case you want to do anything more advanced there.
* Figure-making software access detailed [here](https://github.com/Teichlab/figure-software).
* If you need to install any software on your machine, open the Self Service app and search for Elevate to Admin.

For most analysis needs, JupyterHub is likely to suffice. There are more specialised resources available if need be:
* CellGenIT offer interactive access to GPUs, fill in the [google form](https://docs.google.com/forms/d/e/1FAIpQLSeTgn0_60_5uovO11bMizbCQv6IuUCVUjLuCJAaUbt5lKaPlA/viewform). Set up rclone like outlined above to have a way to communicate between the farm and the GPU notebook.
* Follow the [basecloud](https://github.com/Teichlab/basecloud) tutorial to create an OpenStack instance. This has been largely antiquated by JupyterHub for everyday practical working, but maybe you need root access, `apt-get` or something.
