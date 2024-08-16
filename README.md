# AppSheet Bootcamp

The aims of this exercise is to build a simple mobile app for **Equipment Inspections** using no-code platform Google’s [AppSheet](https://appsheet.com).

[![Build no-code apps with AppSheet](https://i3.ytimg.com/vi/DjAD81A9nYk/maxresdefault.jpg)](https://www.youtube.com/watch?v=DjAD81A9nYk)

## Project Structure

1. **Data Preparation**
- Create a [Google Sheet](https://workspace.google.com/products/sheets/) with the necessary columns (e.g., Equipment ID, Inspection Date, Status, Reason, etc).

2. **App Creation**
- Connect your Google Sheet to AppSheet.
- Set up the app's user interface, including forms for data entry and views for inspection records.
- Customize the app’s design to make it user-friendly.

3. **Adding Features**
- Define data validation rules for accurate data entry.
- Implement search and filter functionalities to easily find equipment.
- Set up automated workflows to send email notifications for failed equipments during inspections.
- Create reports summarizing inspection results over a specified period.

## Step-by-Step Guide for AppSheet Bootcamp

1. Prepare Google Sheet.
2. Create AppSheet.
3. Interfacing Data Google Sheet.
4. User Interface.
5. Enhanced User Experience.
6. Automate Email Notification.
7. Email Notification with PDF Report Attachment.

## 1. Prepare Google Sheet (5 Steps)

1. Create a new folder named **`Equipment Inspections`** in your Google Drive.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/prepare-google-sheet/AppSheet-01.png" width="800"></a></p>

2. Create a new Google Sheet in the folder.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/prepare-google-sheet/AppSheet-02.png" width="800"></a></p>

3. Rename the Google Sheet title to **`Equipment Inspections`**

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/prepare-google-sheet/AppSheet-03.png" width="800"></a></p>

4. Rename the **`Sheet1`** to **`Equipments`** and add the following columns:
- **`Equipment ID`** (Unique Identifier for each equipment)
- **`Name`** (Name of the equipment)
- **`Description`** (Brief description of the equipment)
- **`Image`** (Link to an image of the equipment)

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/prepare-google-sheet/AppSheet-04.png" width="800"></a></p>

5. Create the **`Inspections`** Sheet and add the following columns:
- **`Inspection ID`** (Unique Identifier for each inspection)
- **`Equipment ID`** (Reference to the Equipment ID from the Equipments sheet)
- **`Status`** (Inspection status, e.g., **Passed**, **Failed**)
- **`Reason`** (Reason for failure, if any)
- **`Date`** (Date of inspection)
- **`User Email`** (Email of the inspector)

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/prepare-google-sheet/AppSheet-05.png" width="800"></a></p>

## 2. Create AppSheet

1. Go to [AppSheet](https://appsheet.com) and click the **`Sign in`** link.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-06.png" width="800"></a></p>

2. Choose **`Google`** as your login platform to AppSheet.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-07.png" width="800"></a></p>

3. Sign in with your Google account.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-08.png" width="800"></a></p>

4. Click the **`Continue`** button to continue.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-09.png" width="800"></a></p>

You have successfully signed in to the AppSheet platform.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-10.png" width="800"></a></p>

5. Click on the **`Create`** button and choose the **`Start with existing data`** option.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-11.png" width="800"></a></p>

6. Provide the name for the app, **`Equipment Inspection`**.
7. Select the category **`Inspections & Surveys`**.

<p align="center"><img src="https://github.com/myduino/AppSheet-Equipment-Inspections/blob/main/references/create-appsheet/AppSheet-12.png" width="800"></a></p>




Configure Data Sources:

AppSheet will automatically detect the Equipments and Inspections sheets.
Ensure both tables are correctly set up in the app’s Data section.