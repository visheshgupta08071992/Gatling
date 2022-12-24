## Understanding Gatling

### What is Gatling?

1.Gattling is a powerful open-source load testing tool, We say it powerful because we can create millions of virtual users and we do not have to generate a separate machines with high CPU and RAM for using Gatling. Gatling is written in Scala and the scripts that we create for our performance Testing can be written in Scala or Java or Kotlin.</br>

2.We can use Gatling as a standalone tool or we can use Gatling with our build Maven,Gradle etc.</br>

3.Gatling is built on top of tool called AKKA which enables Gatling to implement virtual users as messages instead of dedicated Threads, making them very resource cheap.

![image](https://user-images.githubusercontent.com/52998083/209425087-26e6f29c-ea33-4f42-afe9-ee45960d2565.png)

### Ways to use Gatling

There are two ways to use Gatling -

1. Using Gatling as standalone bundle -> Prerequisite here is Java(JDK)
2. Use Gating with Build Tool -> Prerequisite here is Java(JDK),Scala,BuildTool(Maven,Gradle),IDE(Intellij,Eclipse)


## Using Gatling Standalone bundle

### Download and Setup

1. Download Gatling from **https://gatling.io/open-source/** </br>
2. Check gatling.bat file is present for windows and for mac gatling.sh is present within gatling/bin folder
3. Check recorder.bat file is present for windows and for mac recorder.sh is present within gatling/bin folder

![image](https://user-images.githubusercontent.com/52998083/209428935-edb9cf69-bb1a-49a2-9533-e75a42b9a28f.png).

4.Recorder.bat file is used for recording while gatling.bat is used to run our test whether it is created with or without recording.

5.Run the recorder.bat file directly or through cmd using command recorder.bat from path where recorder.bat file is present.

6.Once the Gatling App is opened,Change the recorder modee to HAR Converter

![image](https://user-images.githubusercontent.com/52998083/209429265-b2cb2b6b-8924-4eee-ab02-1d16734a23a8.png)

7.Record a test on browser and download the HAR file

8.Upload HAR file in Gatling recorder and generate script by clicking on Start button.

![image](https://user-images.githubusercontent.com/52998083/209429582-fb81edc1-89f6-4959-bec1-f81773b8f7cd.png)

9.Our script gets stored within Gatling folder -> user-files -> simulations.

10.Run scripts using gatling.bat and check reports.

11.Results gets stored within Gatling folder -> result.


## Using Gatling with Build Tool

1.Prerequisite here is Java(JDK),Scala,BuildTool(Maven,Gradle),IDE(Intellij,Eclipse)

2.Download Scala zip file from https://github.com/lampepfl/dotty/releases/tag/3.1.0

3.Unzip the scala zip and the bin folder path of scala to Envionment Path Variable.

4.Open CMD and check whether is installed using command scala -version

5.Ensure Maven is installed using command **mvn -v** 

6.Install Scala Plugin within Intellij.

7.Clone and download sample scala project from https://github.com/gatling/gatling-tutorial









 







