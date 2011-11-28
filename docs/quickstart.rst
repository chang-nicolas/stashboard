Getting Started
=================

Running Locally
----------------

Download and install the `App Engine SDK for Python <http://code.google.com/appengine/downloads.html#Google_App_Engine_SDK_for_Python>`_.

You'll then need to checkout the Stashboard repository.

.. code-block:: bash

    git clone git://github.com/twilio/stashboard.git`

Open the SDK, choose `File > Add Existing Application...` and select the `stashboard` folder inside the cloned repository. Then click the green "Run" button to start the application.

Visit http://localhost:8080/admin/setup to complete the installation.

Customzing
-------------
Open the `settings.py` file and change the `SITE_NAME`, `SITE_URL`, and `REPORT_URL` options to the desired values. The `CONSUMER_KEY` and `CONSUMER_SECRET` values don't need to be changed

Deploying
-------------

Before you can deploy to Appspot, you'll need to `create an application on App Engine <https://appengine.google.com/start/createapp>`_. Once you've done that, update the `app.yaml` with your application id.

Hit the "Deploy" button, wait a couple of seconds, and then naviagate to `http://{application-id}.appspot.com` to enjoy your new status dashboard.

**REMINDER:** You need to go to `http://{application-id}.appspot.com/admin/setup` to complete your installation.
