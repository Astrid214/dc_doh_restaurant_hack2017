# Welcome to the DOH Food Establishments Inspections Project!

## All you need to know for today

[Project Collaborative Doc](https://docs.google.com/document/d/1om26hcKqqP4raQteocMEOLAkF9ezKg0c94qeVGh0YfY/edit)

[DOH Rats Project project GitHub Repo](https://github.com/jasonasher/dc_doh_hackathon) (We're sharing resources-- there are issues related to restaurant data you can close out there)

[Restaurant Inspection Data Scraing Repo](https://github.com/jasonasher/dc_restaurant_inspections)

[Restaurant Inspection App Repo](https://github.com/mrkem598/DC_restaurant_inspection_app)

*Add any data analysis work to this Repo or to [Project Collaborative Doc](https://docs.google.com/document/d/1om26hcKqqP4raQteocMEOLAkF9ezKg0c94qeVGh0YfY/edit)

## DropBox Folders w/ Data:

[Restaurant Health Inspections](https://www.dropbox.com/sh/a1ucls1dwytc22k/AADV6Eic8Ym7XoMQfbvHp14Ia/Data%20Sets/Restaurant%20Inspections?dl=0)

[Basic Business License Data](https://www.dropbox.com/sh/a1ucls1dwytc22k/AAC35BXL3gZP7cUwdVBpOEMPa/Data%20Sets/Basic%20Business%20Licenses?dl=0)

[Lots Other Data](https://www.dropbox.com/sh/a1ucls1dwytc22k/AAAfsyQJU2VTCdY0XYzpd9Jaa/Data%20Sets?dl=0)

# Background Info
## Food Safety/Restaurant Inspections
[Understanding Food Establishment Inspections](https://doh.dc.gov/service/understanding-food-establishment-inspections)

Food establishments that sell or serve food to the public must apply for a health permit and be inspected for compliance with the DC Department of Health. These establishments include restaurants, school cafeterias, bakeries, mobile food vendors, and markets. The majority of the permitted food service establishments in Washington, DC receive two routine unannounced food safety inspections per year. DOH follows the federal food code and only closes an establishment for critical violations that cannot be corrected while an inspector is onsite (for several hours) and poses immediate harm to residents and visitors to the District. The purpose of a food safety inspection is to ensure the food is being handled properly from preparation through serving. DOH seeks understanding as to whether or not there are common factors of establishments that can guide future training efforts for business owners and staff or that may help the department allocate staff resources in a more efficient and effective manner. Note that the number of times annually that a food retail location is inspected is based on its risk category.Any problems observed are recorded on the inspection report and the manager is taught the correct procedure or method immediately

## The goals for our project

* Data analysis/visualizations of the DOH restaurant inspection data report
* Develop a model featuring relationships between location, risk category, serious food-safety violations, closure etc.
* Develop an application for DOH staff that tracks upcoming inspections, displays information on expiring licenses, and aids in the efficient prioritization of follow-up inspections.

# Join the projects

1. Add your name to our sign up sheet in the "Sign up sheet" tab
2. Find an available task under Github Issues, assign yourself or your group to the task, and get hacking!

We are recruiting individuals for the following types of tasks:

* Data cleaning: Help us convert raw data frames into clean feature datasets that are ready to integrate into models!
* Data visualization: Look at the available datasets (See the "Dataset summary" tab in our sign up sheet, chat with DC DOH agency representatives about maps and visualizations of interest, and create the visualizations!
* User interface/experience (UI/UX):
* Build out features for our existing 311 data portal in R Shiny (http://dc311portal.codefordc.org/)
     <br></br>i. Design and start to develop a web application for the public to view DOH inspection reports for food retail establishments
    <br></br>ii. Design and start to develop an application for DOH staff that tracks upcoming inspections, displays information on expiring licenses, and aids in the efficient prioritization of follow-up inspections.
   <br></br>iii. Project management: Interested in helping us manage the project? Chat with one of the project leads!

# Contribute your code

Start by forking this repository to your Github account (click "Fork" in the top right). Then clone the forked version of the repository to your computer using the URL listed under "Clone or Download".
```
$ git clone <url-of-your-fork>
```
We use a triangular workflow - you should push to your Github account's fork, but fetch/pull from this master repository. Setting this up requires adding a remote to this repository account. "Git clone" will have created your repository in a new folder called "dc_doh_hackathon". Use these commands to add the remote to that new folder:
```
$ cd dc_doh_hackathon
$ git remote add dohhackathon https://github.com/jasonasher/dc_doh_hackathon.git
$ git remote -v
  #you should see this:
  dohhackathon       https://github.com/jasonasher/dc_doh_hackathon.git (fetch)
  dohhackathon       https://github.com/jasonasher/dc_doh_hackathon.git (push)
  origin          <your/forked/url> (push)
  origin          <your/forked/url> (fetch)
```
Now instead of plain git push and git pull, use these:
```
$ git push origin <branch-name>         #pushes to your forked repo
$ git pull dohhackathon <branch-name>   #fetches and merges from the dohhackathon repo
Here’s more information on setting up triangular workflows (scroll to “Improved support…”).
```
Never worked with a triangular workflow before? Ask a project lead for help.
