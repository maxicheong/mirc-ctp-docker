# CTp Builder

This will eventually be a [packer](https://www.packer.io/docs/command-line/build.html) configuration to generate build instances (images) on different cloud platforms for MIRC-CTP. I am just in the process of testing!


	packer build builder.json 
	googlecompute output will be in this color.

	==> googlecompute: Checking image does not exist...
	==> googlecompute: Creating temporary SSH key for instance...
	==> googlecompute: Creating instance...
	    googlecompute: Loading zone: us-west1-a
	    googlecompute: Loading machine type: n1-standard-1
	    googlecompute: Loading network: default
	    googlecompute: Requesting instance creation...
	    googlecompute: Waiting for creation operation to complete...
	    googlecompute: Instance has been created!
	==> googlecompute: Waiting for the instance to become running...
	    googlecompute: IP: 104.196.236.212
	==> googlecompute: Waiting for SSH to become available...
	==> googlecompute: Connected to SSH!
	==> googlecompute: Waiting for any running startup script to finish...
	==> googlecompute: Startup script not finished yet. Waiting...
	==> googlecompute: Startup script not finished yet. Waiting...
	==> googlecompute: Startup script, if any, has finished running.
	==> googlecompute: Deleting instance...
	    googlecompute: Instance has been deleted!
	==> googlecompute: Creating image...
	==> googlecompute: Deleting disk...
	    googlecompute: Disk has been deleted!
	Build 'googlecompute' finished.

	==> Builds finished. The artifacts of successful builds are:
	--> googlecompute: A disk image was created: mirc-ctp-test-58151473-5671-eed2-1511-c8afdb680a36

