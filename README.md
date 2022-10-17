
# Case Study: Build and deploy Web Applications in Private or Public Cloud

Contributors to this document: Danish Kamaal

Regis University

MSSE 695: Software Engineering Res & Dev

Professor: Dr. Kevin Pyatt

This case study explores processes and challenges of deploying Web Applications in Private or Public Cloud. It also includes Installation procedures of Private Cloud “NextCloud” on Linux Ubuntu Server. As Installation and Running Private Cloud is important, monitoring of web service or private cloud is also of paramount importance to have continuous availability for users. During Software Engineering Research & Development course we learned process to Install Linux OS, LAMP Stack Installation using the available instructions in “Recipe”.  NextCloud is open source private cloud, End to End encrypted solution, which user can customize it according to their need. NextCloud Web Service, Disk Usage and NextCloud Database is monitored using Nagios, which is open source monitoring tool for computer systems. Nagios Core is used as the version for monitoring services on Local Host and Remote Host.

Nagios Monitoring Tool monitors different services on localhost as well as other hosts. It allows remote monitoring using Nagios Remote Plugin Executer (NRPE) that has to be installed on each host that is being monitored. NextCloud performance such as Disk Usage, availability and database performance is monitored using Nagios. User can select services and update the configuration files. To achieve Private Cloud Installation and monitoring using Monitoring Tool various aspects are considered such as version of Scripting Language (PHP for this case study), Database Server Libraries (MySQL for this Case Study) and available services for a Monitoring tool version (Nagios Core for this case study)


# Conclusion

As a team we were able to successfully Install Nagios Monitoring tool on Server 07 of Regis Cloud. At the same time we were able to Install NRPE (Nagios Remote Plugin Executer) on Server 02. We were able to prove that we can monitor services on Nagios Server (Server 07) and Remote Server (Server 02) with correct configurations in place along with commands defined to access those services data. To take it further we Installed Private Cloud “NextCloud” on Server 02 and proved that we can monitor Private Cloud running on remote server (Server 02) as well. To prove the Hypotheses Database and NextCloud Web Service were monitored and data was collected by uploading and downloading data to NextCloud.

#Acknowledgements

I would like to express my special thanks of gratitude to Dr. Pyatt who gave me opportunity to do Research and this Case Study. Special thanks to Nagios Team Members Brenda Palmer and Mohammad Alsharayri who worked with me on Research Project. I learned a lot during Labs and Research Project Sessions.

# References

Expedient (2021) Retrieved from https://expedient.com/knowledgebase/blog/2014-06-05-private-vs-public-cloud-whats-difference/

Google Cloud (2021) Deploying to App Engine Retrieved from https://cloud.google.com/build/docs/deploying-builds/deploy-appengine

Linthicum, D. S. (2017). Cloud-Native Applications and Cloud Migration: The Good, the Bad, and the Points Between. IEEE Cloud Computing, 4(5), 12–14. https://doi.org/10.1109/MCC.2017.4250932

Medium.com (2019) https://medium.com/google-cloud/hosting-web-applications-on-google-cloud-an-overview-46f5605eb3a6

Pyatt, K. (2021). Full-Stack Lab III PDF. Anderson College of Business & Computing, Regis University

Pyatt, K. (2021). Recipe for File Transfer-Client and Remote PDF. Anderson College of Business & Computing, Regis University

Snyder, E., Hoeve, E., & Watermeyer, K (2021). Nginx Team Research Project Recipe. Anderson College of Business & Computing, Regis University

Stackify (2020). What is LAMP Stack? Retrieved from https://stackify.com/what-is-lamp-stack/

Techguide (2021). How to Install and Configure Nextcloud Hub 21. Retrieved from https://techguides.yt/guides/how-to-install-and-configure-nextcloud-hub-21/

Weinman, J. (2016). Migrating to—or away from—The Public Cloud. IEEE Cloud Computing, 3(2), 6–10. https://doi.org/10.1109/MCC.2016.45

Wojciech, K & Beltowski, P (2016) Learning Nagios – Third Edition. Packt Publishing. [O’Reilly Version] Retrieved from https://learning.oreilly.com/library/view/learning-nagios/9781785885952/


