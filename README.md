## New starter checklist

First off, hello and welcome to Teichlab! Below you'll find a list of things that are good to set up as a new person in the lab. 

**Main things to do:**
* Use your Sanger login credentials to get access to [VPN](https://www.sanger.ac.uk/covid/).
* Await an invitation email to Slack. Once you register, you'll see a message from Slackbot. Interact with the bot and select Teichlab once prompted for a team to join. If something doesn't work out in the process, write Krzysztof Polanski (kp9), Alicja Wilk (aw33) or Martin Prete (mp33).
* Determine your admin person for two following tasks. Find the highest person on this list who is not on holiday as per Slack:
    * Krzysztof Polanski (kp9)
    * Shuang Li (sl37)
* Send the following email to servicedesk (at sanger.ac.uk), with your admin person on CC for approval:
```
Please add me to Unix group team205, and LSF group teichlab. Please create an iRODS account for me, and then pass this ticket to ISG to add me to iRODS group team205#archive.
```
* Make a GitHub account if you don't have one. Please ensure that you fill in your full name in the account details for ease of identification. Then do the following:
  * Email cellgeni (at sanger.ac.uk), specifying your GitHub user name and the fact that you're from Teichlab, asking for access to JupyterHub. Once granted access, go to https://jhub.cellgeni.sanger.ac.uk/ and select the Teichlab image from the list after logging in with your GitHub account. Enjoy an environment packed full of relevant analysis packages pre-installed for you, just select `teichlab` from the quickstart launch thing when creating notebooks.
  * Write your admin person on Slack with your GitHub user name, asking for membership in the Teichlab GitHub organisation, granting access to [Scripts](https://github.com/Teichlab/mapcloud/tree/master/scripts) and other "Teichlab public" repositories.

**More specialised:**
* Write servicedesk to enrol for a farm course, which will allow cluster job submission once completed.
* Set up [rclone](https://cellgeni.readthedocs.io/en/latest/rclone.html) for Google Drive communication. Please avoid putting any sequence data (FASTQ/BAM/CRAM being the most common) there due to ethics.
* JupyterHub offers [documentation](https://cellgeni.readthedocs.io/en/latest/jupyterhub.html) in case you want to do anything more advanced there.

For most analysis needs, JupyterHub is likely to suffice. There are more specialised resources available if need be:
* CellGenIT offer interactive access to GPUs, fill in the [google form](https://docs.google.com/forms/d/e/1FAIpQLSeTgn0_60_5uovO11bMizbCQv6IuUCVUjLuCJAaUbt5lKaPlA/viewform).
* Follow the [basecloud](https://github.com/Teichlab/basecloud) tutorial to create an OpenStack instance,
