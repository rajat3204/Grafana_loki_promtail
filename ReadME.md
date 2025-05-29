## Create alert
> go to grafan console
> crwate or import the dashboard to see the metrics
> clikc on the dashbaord > import > use 1860 > load > choose prometheus > save and test
> click on the created dashboard
> there is a box for ram > click on three dots > more > create new alert rule > entername(ProjectNmae_disk_alert) > in Expression choose threshold and set your threshold to 80 > add folder what you want  > create evaluateion with default settings > 
Configure new contact point  >                        # name > email > define emails > save contact point)
refresh contactpoint and choose that yu created > 
> configure notification msg > Summay (PRoject_name : disk alert usage)
> description (add the 80 percent thresohl message here)
> below enter the runbook url if you want to see the dashboard when any one get the alert and then veiw the alert window\
