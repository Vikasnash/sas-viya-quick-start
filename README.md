# SAS Viya Quick Start Videos and Supporting Files

## Overview

[The SAS Viya Quick Start video series](https://video.sas.com/category/videos/sas-viya-quick-start) provides tutorials for many of the SAS Viya applications. The videos are designed to allow users to follow along in the software to enhance their learning experience. This repository provides the files referenced in the videos so that you can configure your environment to follow along.  

### Quick Start Video Series

The following videos are included in the Quick Start series:
- [SAS Viya and the Analytics Life Cycle](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6325462141112/sas-viya-and-the-analytics-life-cycle?autoStart=true)
- [Discover Information Assets with SAS Information Catalog](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6326134225112/discover-information-assets-with-sas-information-catalog?autoStart=true)
- [Explore and Visualize Data with SAS Visual Analytics](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6323595794112/explore-and-visualize-data-with-sas-visual-analytics?autoStart=true)
- [Build Models with SAS Model Studio](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6326334754112/build-models-with-sas-model-studio?autoStart=true)
- [Manage Models with SAS Model Manager](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6326134528112/manage-models-with-sas-model-manager?autoStart=true)
- [Develop SAS Code with SAS Studio](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6325460656112/develop-sas-code-with-sas-studio?autoStart=true)
- [Build Flows with SAS Studio](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6325462242112/build-flows-with-sas-studio?autoStart=true)
- [Create Custom Steps with SAS Studio](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6347011003112/create-custom-steps-with-sas-studio?autoStart=true)
- [Accelerate Code in SAS Cloud Analytic Services](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6326133063112/accelerate-code-with-sas-cloud-analytic-services?autoStart=true)
- [Prepare Data with SAS Data Studio](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6332730394112/prepare-data-with-sas-data-studio?autoStart=true)
- [Share and Collaborate with SAS Drive](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6332187252112/share-and-collaborate-with-sas-drive?autoStart=true)
- [Use Python Code with SAS Studio](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6332185094112/use-python-code-in-sas-studio?autoStart=true)
- [Use the Python SWAT Package on the SAS Viya Platform](https://video.sas.com/detail/videos/sas-viya-quick-start/video/6332198984112/use-the-python-swat-package-on-the-sas-viya-platform?autoStart=true)
- [SAS Visual Analytics 1 for SAS® Viya: Basics](https://learn.sas.com/course/view.php?id=241)
- [SAS® Visual Analytics 2 for SAS® Viya®: Advanced](https://learn.sas.com/course/view.php?id=244)
- [Explore and Visualize: Getting Started](https://learn.sas.com/mod/scormddl/scormplayer.php?scoid=2348&language=1196&scormid=1196)

---

# Top 5 Things to Know for Using SAS Visual Analytics

### [Summary](https://communities.sas.com/t5/SAS-Communities-Library/Top-5-Things-you-need-to-know-for-using-SAS-Visual-Analytics/ta-p/855258)
There you have it, the Top 5 things to know for using SAS Visual Analytics.

1. **Select Data, Pick an Object, & Assign Roles**  
   Begin by selecting your dataset, choosing a visualization object (e.g., bar chart, pie chart), and assigning roles like category or measure. SAS Visual Analytics can also auto-chart based on the data you drag onto the canvas.

2. **Report Prompts & Page Prompts**  
   Use prompts to filter data dynamically. Report prompts apply across the entire report, while page prompts affect only the current page, allowing for more targeted filtering.

3. **Actions: Automatic & Manual**  
   Set up interactions between report elements. Automatic actions like brushing highlight related data, while manual actions allow for customized linking and filtering.

4. **Multiple Data Sources**  
   Integrate and analyze data from various sources within a single report. Use joins or linking techniques to relate different datasets effectively.

5. **Create New Data Items**  
   Enhance your reports by creating calculated fields, aggregated measures, or custom categories directly within SAS Visual Analytics.

---

### Installation

1.	Visit https://github.com/sassoftware/sas-viya-quick-start and click **Code** > **Download ZIP**. 
2.	Unzip the files to your local machine. By default, the files will be in a folder named **sas-viya-quick-start-main**.
3.	In SAS Viya, select the Applications menu in the upper left corner and select **Develop Code and Flows**. SAS Studio launches. 
4.	In the Navigation pane on the left, select the **Explorer** icon. 
5.	Expand ![image](https://github.com/sassoftware/sas-viya-quick-start/assets/22669486/d8c5b592-25ba-4b81-9e9e-795cb5efcee2). Navigate to your preferred location for storing the files. You must have write access. Right-click on the desired folder and select **New folder**. Name the folder **quick-start**.  
NOTE: Your environment may have a different label other than **Files**, but the icon will look the same. The file location demonstrated in the video is **Files** > **data** > **quick-start**.
6.	Select the new **quick-start** folder and click the **Upload** button. 
7.	Click **Add**, then navigate to the files you unzipped on your local machine. Press **Ctrl+A** to select all the files, then click **Open** > **Upload**.
8.	In the Explorer, expand the **quick-start** folder and double-click the **Load_Quick_Start_Data.sas** program to open it. 
9.	Do not make any changes to the code. Click **Run**. Confirm the **HOME_EQUITY** and **CUSTOMER_COMMENTS** tables are listed in the Table Information report.  
NOTE: As you follow along in your environment, the **HOME_EQUITY** and **CUSTOMER_COMMENTS** tables will be in the **Casuser** caslib. 

## Contributing

We do not accept contributions for this project. 

## License

This project is licensed under the [Apache 2.0 License](LICENSE).

## Additional Resources

**Required**. Include any additional resources that users may need or find useful when using your software. Additional resources might include the following:

* *Link to videos on SAS Video Portal (once posted)*
* [SAS Viya Community](https://communities.sas.com/t5/SAS-Viya/ct-p/viya)
* [SAS Viya Learning and Support](https://support.sas.com/en/software/sas-viya.html)
