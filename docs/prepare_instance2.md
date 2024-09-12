# Prepare the BIG-IP Next instance to import into CM

1\. Console or SSH into your instance and login with default username/password set through the OVA or cloud-init.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-12/a46f319c-5253-4ded-ab50-cbf500ea8f59/File.jpeg?tl_px=0,0&br_px=859,480&force_format=jpeg&q=100&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=224,69)


2\. Type "setup" to set basic configuration prior to importing into Central Manager.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-12/9e5baed2-0c55-4909-939c-744cb91ada4c/screenshot.jpeg?tl_px=0,0&br_px=407,179&force_format=jpeg&q=100)


3\. Enter the hostname, confirm DHCP or static IP

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-12/57148652-5ae1-4caa-8b0f-0fd5b5462fe5/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=982,263&force_format=jpeg&q=100&width=983&wat_scale=87&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=303,811)


4\. You can optionally set NTP and the initial VLAN here but we recommend you perform this after importing into CM.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-12/ce8428bb-3a4d-469a-af47-1fb101a6c093/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=982,131&force_format=jpeg&q=100&width=983&wat_scale=87&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=303,570)


5\. Finally set the password CM will use to import the instance.

\
*Please note that you must perform this password reset anytime the instance has been factory reset or removed from CM*

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-12/a17fe705-c743-4d12-aa1d-2ac484dbe05b/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=975,118&force_format=jpeg&q=100&width=983&wat_scale=87&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=306,418)


Tip: Your instance is ready to import into Central Manager!


