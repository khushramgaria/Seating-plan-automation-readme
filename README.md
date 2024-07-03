# Seating Plan Automation

Welcome to **Seating Plan Automation**! This tool is designed to help users quickly and efficiently create seating plans that would otherwise be manually created in Excel. With just a few steps and the correct data, you can generate a complete seating plan in minutes.

## Overview

The **Seating Plan Automation** website simplifies the process of creating seating plans. By providing data in a specific format, the tool processes the information and generates a seating plan that can be downloaded and further edited if needed.

## How It Works

### Steps to Generate a Seating Plan

1. **Data Preparation**:
   - Reference: Baba Farid Group of Institutions strategy and data.
   - Download the student data (cultists) from the official university portal. Also I shared the sample data in this repo.

2. **Data Conversion**:
   - Open the website [https://sitting-plan-automation.vercel.app/](https://sitting-plan-automation.vercel.app/).
   - Click on the `Convert Excel` button at the bottom of the page.
   - Upload the downloaded cultists Excel data.
   - The tool will process and download a single Excel file containing the needed data.

3. **Uploading and Confirming Data**:
   - Click `Back To Upload Excel`.
   - Click on `Choose File` and select the file that was downloaded after conversion.
   - Click on `Confirm` to proceed.

4. **Selecting Exam Type**:
   - A popup will appear to select the exam type:
     - **Same Exam**: If all students have the same exam or most have the same exam with a few exceptions.
     - **Different Exam**: If students have different exams.

5. **Class Selection**:
   - Select the classes from the provided window.
   - Edit classes by clicking on `Edit Classes` if needed.
   - Click `Select All` if you want to include all present classes.
   - Confirm your selection by clicking on `Confirm Classes`.

6. **Seating Arrangement**:
   - Choose the seating arrangement:
     - Two students on one bench
     - Three students on one bench
     - Four students on one bench
   - The seating plan will be generated successfully.

7. **Download and Editing**:
   - Click on `Proceed` to download the seating plan in PDF format.
   - Generate and download the attendance sheet.
   - Edit tables as needed, such as moving students' roll numbers or updating detained students' details.

8. **Teacher Assignment**:
   - Assign teachers to rooms:
     - View the room details and strength.
     - Select teachers from the dropdown menu.
     - Click `Assign` to generate a table with the details.
     - Download the updated table.
   - Manage teachers on the homepage by clicking on `Manage Teachers`.

## Important Points to Note

1. **Data Format**:
   - Only the specific format provided should be used to convert the data.
   - The converted Excel data must also adhere to a specific format for generating the seating plan.

2. **No Back Button**:
   - There is no back button because data flows from one component to another, and reloading can cause data loss or undefined states. Please be patient while using the website.

3. **Consistency in Editing**:
   - If you edit tables after generating the seating plan, maintain consistency by updating all related tables (e.g., student strength, attendance, teacher assignments).
   - Although editing may introduce inconsistencies, it is necessary to ensure accuracy in cases where data is not entirely satisfactory.

## Conclusion

**Seating Plan Automation** significantly reduces the time required to create seating plans manually. While not perfect, it allows for editable tables to address specific needs and ensures a more efficient planning process.
