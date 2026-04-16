# Project Architecture

This is the project architecture for Claude to follow for the Emento-Camera project.  
  
**Goal of the project**
- Build a functional prototype to showcase an idea
- The idea is to translate paper notes into relevant content that can be added into the Emento App
- For example: a piece of paper with key location details for a surgery department could be input into the app instead of a generic hospital location
  
**Who will use this prototype?**
- This prototype will be used by people, we will call them ‘testers’
- They will test the prototype, click through and use it’s functions to understand the goal and key concept behind the solution that is being prototyped
- Testers have a deep understanding of the app, this is to communicate internal ideas

## Start Page
- The goal is to tell the tester what feature they are testing
- In this case: a camera input option to take a note from a nurse and input the relevant information into the Emento App
- The center of the page should be a button with an icon of a camera with a “+” symbol
- Below the button is the text: “Add Information To Your Digital Care Guide”

**Key Action:**
- Testers can click the camera+ icon to navigate to the camera function
- NO OTHER INTERACTIONS

## Camera
- Should open the native camera app on the phone
- Allow testers to take a photo

**Key Action:**
- Take a photo using the native camera app
	  

## Analyse Image
- The app needs to analyse the photo and determine if:  
	A) The image is a note from the nurse with appointment information  
	B) The image is a pain medication schedule for the patient
- Analyse the photo and then provide a summary screen that says if the image is option A or B and make a summary of the information on the note in text format
- For the purposes of the prototype: alternate between these two images to just communicate the idea (doesn’t need to functionally work with AI just yet)  
	- The images are located in an image folder in the directory

| Mock Outcomes                      | Image                                          | Text from Image                                                                                                                                                                 |
| ---------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Option A: Nurse Note               | ![Example Image to Use for Prototype][image-1] | Afdeling 0661 Dato: 23/12 Klokken: 7:30 Fastede 6 timer inden mødetid Tørstede 2 timer inden mødetid                                                                            |
| Option B: Pain Medication Schedule | ![Example Image to Use for Prototype][image-2] | Paracetamol - Start 23/03 - Slut 27/03 2 tablet (2x500mg) Morgen, Middag, Aften, Nat  Tramadol - Start 23/12 - Slut 25/12 - 1 tablet (1x50mg) efter behov - Højst 4 gang daglig |

**Key Actions:**
- There should be a ‘back button’ in the upper left-hand corner so the tester can go back to the “Start Screen”** - There should be a “Add to Care Journey” button at the bottom
	  

## Show Updated Care Journey

- After a tester clicks on the ‘Add to Care Journey’ button they should be shown the relevant app page (appointment or timeline - screenshots to use as visual examples are provided below)
- The updated information should be added to the app
- For example, the date and time or a new task item to take medication
- To communicate the idea clearly, highlight the added information in a brighter green and then have the color fade back to match the visual style, as if the new item is highlighted for a few seconds after the page loads and then subtly fades away

**Screens to base the relevant app page:**
 ![Appointment Page][image-3] ![Timeline Page][image-4]  
  
Notes:
- Use these as starting templates for what content and how to display, but adapt to fit the visual style of the prototype and remove unnecessary details (fx the banner at the top saying the journey is done)
- Make it look like the rest of the app prototype, as if it is part of the same project, not a completely new screen - it should feel seamless  

**Key Actions:**
- There should be a ‘back button’ in the upper left-hand corner so the tester can go back to the “Start Screen”** 

[image-1]:	file:///Users/francescadesmarais/Downloads/IMG_0545.jpg
[image-2]:	file:///Users/francescadesmarais/Downloads/IMG_0547.jpg
[image-3]:	file:///Users/francescadesmarais/Downloads/IMG_0544.PNG
[image-4]:	file:///Users/francescadesmarais/Downloads/IMG_0546.PNG