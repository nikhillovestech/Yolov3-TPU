# Yolov3-in-Tensorflow(TPU & GPU)

This is Yolov3 code for Cloud TPU.

First you need to create Google Cloud Storage Bucket here is the tutorial https://cloud.google.com/storage/docs/creating-buckets and then create tfrecords of your data and upload to your Cloud Storage Bucket.

Now lets create Cloud TPU(preemptible) here is the tutorial https://cloud.google.com/tpu/docs/preemptible and then create compute instance here is the tutorial https://cloud.google.com/compute/docs/instances/create-start-instance

Now lets setup your compute instance here is the tutorials https://medium.com/google-cloud/set-up-anaconda-under-google-cloud-vm-on-windows-f71fc1064bd7

Now give permissions to your Cloud Storage Bucket so that your Cloud TPU access your Cloud Bucket for that copy your TPU service account and follow the tutorial https://cloud.google.com/tpu/docs/storage-buckets

Yolo_checkpoint.ckpt link https://drive.google.com/open?id=1t1PksAEcwb9Ux5oTbGxSnLPawawt2ME3 upload it to your bucket.

Change the locations of tfrecords file and checkpoint, TPU ip, GCP Project, TPU Zone in the notebook.

Now that you have setup your environment, lets start training type command jupyter-notebook in terminal and run notebook.
