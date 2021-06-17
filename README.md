![ddddddd](https://user-images.githubusercontent.com/58957744/122457740-96e9e900-cf74-11eb-8619-e66fda327463.png)

# [Audience and Affiliations with Tableau](#Table-Of-Contents)
I made an analysis for the audience and affiliations of the Partido Libertario Mx. Some of the insights are clearly explained in the conclusions page.
**Watch the entire visualization online** [here](https://public.tableau.com/app/profile/jorge.pablo/viz/AudienciaPlib2021/AudienciaFByAfiliados)

You can start by reading the results or go directly to the [table of contents](#Table-Of-Contents).

# [Results](#Table-Of-Contents)
All of the results are explicitly written in the presentation. The orange color means that those are the conclusions.

**TRANSLATION**
*  **Mexico's center: Mexico city, Mexico's State, Hidalgo, Queretaro, Guanajuato, will be the cradle of libertarianism in Mexico. We must start to hold public events and grouping our affiliates there to grow the affiliates on each state and start to formalize the organization.**
*  **We need more female audience, the proportion of males is too high, so it is a must to propose actions congruent with female audiences, liberal feminism is one of those.**
*  **The events with libertarian public figures are the best we can hold, they attract many people, so we must do two things, try to hold more events with them and develop our own intern personal brands on libertarianism.**
*  **To take our internal personal brands to make content for us.**
*  **Our best states outside the Mexico's center are industrial states so in the future those will be our levers to grow.**
![conclusiones](https://user-images.githubusercontent.com/58957744/122263587-39826900-ce9c-11eb-97d3-cf1238688e88.png)

**Some other visualizations with insights in orange color.**

![afiliados](https://user-images.githubusercontent.com/58957744/122263790-7189ac00-ce9c-11eb-837b-35f42d2fe109.png)

**The events when we had the most affiliates were months that match good reach on facebook like Gloria and Milei on February 2021**
![afiliadosplus](https://user-images.githubusercontent.com/58957744/122263800-72bad900-ce9c-11eb-9473-d4176bc9c7f9.png)

**The actual facebook audience is dominated by male 77.7%, our best age range are males between 25-34, same range for women**
![audience](https://user-images.githubusercontent.com/58957744/122265408-4ef89280-ce9e-11eb-9e97-9897637a1265.png)


# Table Of Contents

* [Audience and Affiliations with Tableau](#Audience-and-Affiliations-with-Tableau)
* [Results](#Results)
* [Tools And Libraries](#Tools-And-Libraries)
* [Data Wrangling](#Data-Wrangling)


# [Tools And Libraries](#Table-Of-Contents)
  * Python 3.7
  * Pandas 1.1.5
  * Numpy 1.19.5
  * Datetime
  * Excel
  * Tableau

# [Data Wrangling](#Table-Of-Contents)
The wrangling was done on the master file I use to clean their data, the title you should look for is Afiliaciones there I clean the data, to see the entire document and more in detail comments I added [click](https://github.com/JorgePablol/Audience-and-Affiliations-Tableau-PLibMx/blob/main/Libertarian_cleaning.ipynb) if the document don't open reload or download and open it with Google Colab. 

## Reading And Inspecting The Data
![Screenshot from 2021-06-16 11-31-24](https://user-images.githubusercontent.com/58957744/122258286-8105f680-ce96-11eb-8a19-ca53249e7080.png)

## Cleaning And Saving
**Trying to skip some code lines after realizing this was going to be repetitive.**

![Screenshot from 2021-06-16 11-34-20](https://user-images.githubusercontent.com/58957744/122258821-1bfed080-ce97-11eb-8738-ce85a172997f.png)

**In the future I should convert this entire code into a function and also add more regex. Anyway I was kind of burned out at that time to think on a better solution, this worked and cleaned the entire dataset, and also it can work as a script.**

![Screenshot from 2021-06-16 11-34-30](https://user-images.githubusercontent.com/58957744/122258887-3042cd80-ce97-11eb-8cb2-d5d60e81d7b9.png)

**Deleting affiliates from other countries than Mexico, skipping some lines of codes for Baja California and saving the file**

![asd](https://user-images.githubusercontent.com/58957744/122266465-71d77680-ce9f-11eb-8dac-cee84cec9c3b.png)




