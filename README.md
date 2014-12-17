Running on OpenShift
--------------------
Get a copy of the OpenShift Primer presentation online with this project.

Install with one click
----------------------
ck to  install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to  install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.4&initial_git_url=https://github.com/eschabell/openshift-preso-openshiftprimer.git&name=primer)


Manual setup on OpenShift
-------------------------
Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create primer -t php-5.4 --from-code git://github.com/eschabell/openshift-preso-openshiftprimer.git

That's it, you can now start your workshop at:

    http://primer-$your_domain.rhcloud.com

![Cover Slide](https://raw.githubusercontent.com/eschabell/openshift-preso-openshiftprimer/master/php/cover.png)
