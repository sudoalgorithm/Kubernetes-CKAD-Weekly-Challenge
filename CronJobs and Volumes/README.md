Todays Task: CronJobs and Volumes

Create a static PersistentVolume of 50MB to your nodes/localhosts /tmp/k8s-challenge-3 directory.

Create a PersistentVolumeClaim for this volume for 40MB.

Create a CronJob which runs two instances every minute of: a pod mounting the PersistentStorageClaim into /tmp/vol and executing the command hostname >> /tmp/vol/storage.

We only need to keep the last 4 successful executed jobs in the cronjob history.

Check your local filesystem for the hostnames of these pods with tail -f /tmp/k8s-challenge-3/storage.
