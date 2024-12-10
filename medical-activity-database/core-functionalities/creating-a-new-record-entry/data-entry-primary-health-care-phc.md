# Data entry Primary Health Care (PHC)

## Data entry Primary Health Care (PHC)

## TUTORIAL

Health Unit – Data & Analytics

### INTRODUCTION

{% hint style="info" %}
The Data Entry application is used to manually enter routine data on Primary Health Care activities.
{% endhint %}

Here is a list of all data sets/forms relevant to PHC

<figure><img src="../../.gitbook/assets/image (8) (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
There are some important differences in some data sets in the new MAD compared to the old MAD to take into account. Here below you find a table with a comparison.
{% endhint %}

**Data sets Who enters data**

<figure><img src="../../.gitbook/assets/image (9) (2).png" alt=""><figcaption></figcaption></figure>

```
Organisational
unit level
```

**Periodicity**

**PHC Country form** Country Editor Country Yearly

**PHC Population form** Country Editor & Field Users Population

Monthly (Automatically updated every month) **PHC HF monthly report** Field Users Service delivery point Monthly **PHC MHU monthly report** Field Users Service delivery point Monthly **PHC Adhoc Facility support** Field Users Service delivery point Monthly

**PHC Adhoc Central support** Field Users

* Country
* District/First Admin Level Monthly **PHC Other Immunization and Preventive activities**

```
Field Users -Country
```

* District/First Admin Level
  * Population Service delivery point

```
Monthly
```

**PHC COVID- 19 Immunization campaign** Field Users Country Monthly

**OLD MAD NEW MAD WHAT IS CHANGING** Ad-hoc support monthly report

* PHC Adhoc Facility support
* PHC Ad-hoc Central support

In the old MAD ad-hoc support was only available at facility level. In the new MAD ad-hoc support data entry is available at facility level (PHC Adhoc Facility support) **AND** at **central level** (PHC Adhoc Central support). For instance, a central donation made to a governmental entity (i.e. Ministry of Health) will be recorded through PHC Adhoc Central support. Immunization campaign: within PHC Monthly report

```
PHC Other Immunization and Preventive
activities
```

{% hint style="info" %}
Immunization campaigns and preventive commodities are no longer part of the regular monthly reports but will be recorded through a separate data set called “Other Immunization and Preventive activities”. This data set will be used whenever a campaign occurs. It can be recorded at different levels: Country, District/First Admin Level, Population
{% endhint %}

COVID vaccination support: within the adhoc monthly report at facility level

{% hint style="info" %}
PHC COVID-19 Immunization campaign The COVID-19 vaccination support will no longer be recorded as part of the adhoc support. In the new MAD a COVID- 19 dedicated data set is available at country level.
{% endhint %}

Vaccination targets fixed at five years old globally and monitored in the monthly reports

```
Country specific vaccination targets are
defined in the PHC Country form
```

{% hint style="info" %}
In the old MAD vaccination targets were fixed at five years old globally. In the new MAD each country can select in the country form what is the target group for every child vaccine (Polio, MMR, DPT) and monitor in the dashboards vaccination coverage for the relevant target groups.
{% endhint %}

### STEP 1: SELECT ORGANISATION UNIT (OU)

You will need to find and select your Organisation Unit in two ways:

1. Find the name of the Organisation Unit that you would like to enter data for on the drop-down tree menu. Lower levels will be displayed when you click on the "+" sign next to each Organisation Unit. Click on your Organisation Unit on the menu to highlight it orange. This will enter the 'Organisation Unit' in the respective field of your data entry form.

Concerning PHC, after the 1st administration level we have the PHC population level. In the example of the image here below, the Baalbeck – Arsal structure ends with \[POP]. The PHC facility (Aarsal Al Audi Hospital OPD) will be under the population that has been defined in the MAD PHC.

<figure><img src="../../.gitbook/assets/image (10) (2).png" alt=""><figcaption></figcaption></figure>

2. Another quick way to find an Organisation Unit is to use the search box next to the green symbol with the lens above the tree menu. Type in the name or first few letters of your Organisation Unit and select it from the drop-down menu by clicking on it to highlight it orange. This will enter the unit in the Organisation Unit field of your data entry form.

<figure><img src="../../.gitbook/assets/image (11) (2) (1).png" alt=""><figcaption></figcaption></figure>

### STEP 2: SELECT DATA FORM, TIME PERIOD AND RELEVANT GO

In this step, select your data form, the time period and the GO code relevant to your activity. You can also toggle between years, moving a year forward or backward using the 'Prev year' and 'Next year' buttons next to the period entry field.

<figure><img src="../../.gitbook/assets/image (12) (2).png" alt=""><figcaption></figcaption></figure>

### STEP 3: ENTER DATA IN THE FORM

Start entering data by clicking inside the first cell and typing values in manually.

<figure><img src="../../.gitbook/assets/image (13) (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Click on check boxes if any.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (14) (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Most indicators showcase an explanation of their function. If you click on an indicator, a pop-up window showcases its description.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (15) (2).png" alt=""><figcaption></figcaption></figure>

The cells will turn green when the data has been automatically saved in the system.

The cells will turn red when mandatory fields (identified with a star "\*") have not been filled.

Grey fields are those that are completed automatically by the DHIS2 system.

In case an invalid value or a value outside an acceptable range is entered, a pop-up window will detail the problem.

Click on the cell(s) and correct the data. The cell(s) will turn green once you have entered the correct value.

_Note: Your browser may sometimes suggest values that are not built into the DHIS2 forms but have been stored in your browser cache from other websites. You can remove these values using the 'Browser Cache Cleaner' on the applications menu. If the problem persists, the following link guides you on how to disable or clear the AutoFill/AutoComplete in your web browser:_ [How Do I Disable or Clear AutoFill/AutoComplete Information? – iClassPro Support](https://support.iclasspro.com/hc/en-us/articles/218569268-How-Do-I-Disable-or-Clear-AutoFill-AutoComplete-Information)

### STEP 4: VALIDATE DATA

A 'Run validation' button is available in each tab. It applies to the entire form not just the screen that is open. Click 'Run validation' once completed ALL tabs in order to check your data.

<figure><img src="../../.gitbook/assets/image (16) (2).png" alt=""><figcaption></figcaption></figure>

“Run validation” checks for completeness of mandatory fields first and for other rules as a second step. It is important to run a validation check to make sure your data is logical and valid, based on rules built into each form. This step ensures that the data you have entered is accurate.

<figure><img src="../../.gitbook/assets/image (17) (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If all your data is accurate, you will receive a message telling you that the data has passed the validation test once it is complete. If some of the values in your form are inaccurate, you will get a different message telling you that there are errors in your data. It also tells you which values are invalid and which rule needs to be met (e.g. correct data range) for your data to be valid.
{% endhint %}

### STEP 5: CORRECT DATA

You should correct your data if the validation test detected errors on your form. Click on the cells that have invalid data (shown on the validation test message), remove the incorrect value and retype or reselect the correct value. The new value should meet the requirements of the validation rule shown on the validation test message.

<figure><img src="../../.gitbook/assets/image (18) (2).png" alt=""><figcaption></figcaption></figure>

### STEP 6: SUBMIT DATA FOR APPROVAL

When you have finished filling in the form and verified the data, don’t forget to complete it. By clicking on the “complete” button, you are confirming that the data has been entered and verified by you as Field User.

<figure><img src="../../.gitbook/assets/image (19) (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Once completed, a form is considered as submitted for validation to be further checked by the Country Editor. The Country Editor will do the final verification and will approve data. If, after completing the form you realize some corrections need to be made, click first on “incomplete” and make corrections. Then, click on “complete” button again so that the Country Editor knows that it is ready for approval.
{% endhint %}

### STEP 7: HOW TO IMPORT DATA

The purpose of importing data into the MAD from an excel file, originates from the need to work offline. This would help overcoming potential issues linked to the internet connectivity. Furthermore, you may want to share the report with your interlocutors/partners for offline data entry before uploading it in the MAD.

The Health data support team provides you with the excel file to enter data that contains the GO code(s) relevant to your delegation.

Open the file, select the time period, GO code and start entering data in all columns.

<figure><img src="../../.gitbook/assets/image (20) (2).png" alt=""><figcaption></figcaption></figure>

Please note that the file may contain several columns, so be sure to enter all necessary data. The mandatory indicators are marked with an asterisk (\*).

However, in case you do not compile the report entirely, the system will allow you to upload the file as well. You may continue filling the report online, or offline still using an excel file to upload afterwards.

Once finished, save the file on your computer.

In order to start importing data, open the “Bulk Load” application.

You are now ready to import data.

Drag & drop the file that you previously filled and saved (1). Normally the Data Set you selected, the creation date and the number of data values entered will appear. You can now select the concerned Organisation Unit (2). Click on “Select import Organisation Unit”, find and select it. You can also apply the option “Search by name”. Type in the name or first few letters of your Organisation Unit and select it from the drop-down menu. Click on “Import Data” (3).

<figure><img src="../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

Once the uploading completed, a message will confirm if the data import was successful or not.

The Data Set for which you are importing data, may already be partially filled in DHIS2. In such a case the system provides you with two options: **PROCEED** : this option implies that all data values that already exist will get deleted and only the ones included in the spreadsheet will be saved. **IMPORT ONLY NEW DATA VALUES** : the option implies that only new data will be imported.

Select the option convenient with you.

<figure><img src="../../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

In “Data Entry” application you can now search the Data Set for which you imported data. Select your Organisation Unit, relevant Data Set, period and GO code. Your report will contain all imported values.

<figure><img src="../../.gitbook/assets/image (130).png" alt=""><figcaption></figcaption></figure>
