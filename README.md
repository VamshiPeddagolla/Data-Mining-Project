# Data-Mining-Project


Milestone 1 :--- Environment Preparation 

In this stage you will be working with CVAT - you need to install CVAT locally to your laptop/desktop and we urge you to follow the docker setup instructions here

PS: You can also create an account on the cvat.ai site but we dont offer any guarantees that the project can be delivered in its entirety with a cvat instance that is not managed by you.

Submit a github repository with a branch titled ‘milestone-1’ with the readme file containing the CVAT installation instructions you followed and a screenshot of your computer of the login screen. Add as collaborator the TA.






Milestone 2 :--- Data Acquisition 

Go to the HD site and in the left panel select the home area (room) you have been assigned:  bedroom
Select 10 product categories (eg sinks, faucets) that HD sells in each room and that are shown on their promotional videoYou will need to scrape using beautiful soup or retrieve using the Google Custom Search API (better solution), 100 images of each of the selected product categories. Make sure you select products that are not included on the video, meaning if a specific sink is shown on the video, you srape / search different but similar sinks.
Submit a Github branch titled ‘data-acquisition’ and a markdown file called data-acquisition.md containing the code that achieve the milestone and a pytest test file that can show that the code works.




Milestone 3: Annotation 

Upload the images in your CVAT instance and annotate all object categories. This is a manual step and you will need to use the DEXTR cutter.
Write a 2 page summary on how DEXTR works that can be understood by experts.
Ensure that the annotations can be read and seen by the fiftyone tool

Submit a Github branch titled ‘annotation’ containing the annotated dataset in MS COCO format and a markdown file called annotation.md containing the DEXTR description and the link with the 1000 annotated images (10 product categories x 100 images per category. You can collaborate with other teams on the annotation task to share the load.





Milestone 4: Semantic Segmentation 

Use this template or an equivalent template if you are using Tensorflow to implement a semantic segmentation pipeline based on either MaskRCNN (project team number is odd number) or UNet (project team number is even) that will successfully segment the selected objects on the input room video.

You can use frameworks such as https://github.com/facebookresearch/detectron2 for this task.

Ensure you describe how you tuned and what values you ended up using for the network hyperparameters

Submit a Github branch titled ‘segmentation’ containing the segmentation code and a markdown file called segmentation.md containing the full description of the semantic segmentation network you used and the performance results you got.




Milestone 5: Documentation 

Use Jupyterbook to bundle together all the markdown files and publish the project in html - do not commit your html build in github.

Include a copy of the produced video in your Github, showing the segmentations in real time.

Ensure that you merge all the branches into main branch and submit the main branch as the final project deliverable.
