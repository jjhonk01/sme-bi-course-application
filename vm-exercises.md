# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [X] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

To successfully configure and use the append tool with the datasets provided.

#### Context

There are numerous use cases where an append may be needed. Whenever a cartesian join is called for, think of the append tool. Multiplying one dataset by the other, you can expect an error if your source is more than 16 rows. This can be manually bypassed if needed, but prevents long processing times in the case of a mistake.

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Bring an append tool out to the canvas
- Connect the datasets to the correct inputs of the append tool
- Connect a browse tool to the output of the append tool
- Click run and observe results

#### Exercise question:
How many records are in your result?
240

#### End goal:

<img width="1085" alt="image" src="https://github.com/jjhonk01/sme-bi-course-application/assets/70289747/b24be671-4936-4777-a1be-387527e4cfe4">


## 2nd VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [X] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

To successfully configure and use the join tool configured to join by specific fields with the datasets provided.

#### Context

To join by specific fields is best practice when joining two datasets together. Choose whether you need the Left, Right, or Inner Join outputs, and place your browse or output data appropriately. The column used in a join should be unique.

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Bring a join tool out to the canvas
- Connect the datasets to the correct inputs of the join tool
- Configure the join tool to join by specific fields, and select the ID columns from the right and left datasets.
- Connect a browse tool to the output of the join tool
- Click run and observe results

#### Exercise question:
What is the value in the "Specialization:" column in row 3?
Bookkeeping,Securities,Taxation

#### End goal:

<img width="1920" alt="image" src="https://github.com/jjhonk01/sme-bi-course-application/assets/70289747/7c3e4402-02c3-4f84-b1be-c3b8faf2753e">

## 3rd VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [X] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

To successfully configure and use the join tool configured to join by record position with the datasets provided.

#### Context

To join by record position is sometimes necessary when joining two datasets together. Choose whether you need the Left, Right, or Inner Join outputs, and place your browse or output data appropriately. The record position option should only be used when there is 1 row in each dataset or when it can be verified that the rows match up correctly (such as the example in this exercise).

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Bring a join tool out to the canvas
- Connect the datasets to the correct inputs of the join tool
- Configure the join tool to join by record position, no further configuration is needed.
- Connect a browse tool to the output of the join tool
- Click run and observe results

#### Exercise question:
What number matched with letter Z?
26

#### End goal:

<img width="1063" alt="image" src="https://github.com/jjhonk01/sme-bi-course-application/assets/70289747/46cf7e63-e950-4027-9eb9-164a037a1fbe">



