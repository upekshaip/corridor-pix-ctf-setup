# Corridor-Pix (CTF)

## Project Overview:
The CTF project consists of an executable file, ctf.exe, which generates two folders: "flag" and "resources." Inside the "resources" folder, participants find images of a corridor and a room. In the "flag" folder, there is a black-and-white image featuring the number 0 in white on a black background. The project utilizes PyQt5 to create a graphical interface and build a narrative for participants.

## Languages / Frameworks and Libraries:

- Python: The primary programming language for the project.
- PyQt5: Used to create the graphical user interface.
- Image processing libraries (PIL) : Required for pixel mapping and analysis of the provided images.
- Hashlib: For hashing the values

## Functionality of the CTF:
### Part 1: Logical Scenario

- Participants begin in a corridor with 13 doors.
- They choose a door by entering a room number into an input field.
- Each room contains a hashed number.
- Participants must decode the hash into a decimal value, which should match the room number.
- In each room, there is a "Next" button to progress further.
- Participants can enter a flag in the room or return to the corridor.
- The objective is to find the flag, which is the hashed value of the number 0 (representing the corridor's door).

### Part 2: Pixel Mapping
- Participants are presented with a black-and-white image in the "flag" folder.
- They are given no specific instructions but are told to analyze the picture.
- Participants must determine two flags based on pixel counts of the black and white regions in the image.

## User Experience:
- Participants start in a visually engaging corridor with a mysterious atmosphere.
- They must make choices and solve logical puzzles to progress.
- The use of images and hashing adds an element of mystery and challenge.
- The CTF encourages participants to think creatively and explore the provided resources to find flags.
- The graphical interface and interactive elements make the experience engaging and immersive.

## Explanation of the CTF:
When you open the ctf.exe file, two folders are created in your working directory: "flag" and "resources." In the "resources" folder, you'll find pictures of a corridor and a room. Inside the "flag" folder, there's a black and white image displaying the number 0. The background is black, and the number 0 is in white.

I developed an executable file using PyQt5 to craft the narrative. Essentially, the first part is a journey where you enter a corridor, encountering 13 rooms along the way. You must select a single door. The question may seem unusual, but if you input the room number in the field below the corridor picture, you'll be redirected to the corresponding room. In each room, you'll discover a hashed number. If you decrypt this value into decimal, you'll realize that it matches the room number.

In every room, there's a "Next" button. Clicking it takes you to another page where you must enter the flag or return to the room or corridor. However, trying all 13 hashed values won't yield the flag. So, where's the flag? The flag is actually the hashed value of the number 0. Why not 0? Because you entered a corridor, right? To enter a corridor, you must pass through a door – the 0th door. That's how you find the first flag.

The second part revolves around the image in the "flag" folder, which is black and white. I haven't provided any explicit information for this part. I simply instruct you to analyze the picture. If you've truly contemplated what the flag could be, you might deduce it from the image. I'm asking for two flags from the picture. Since the image only has two colors, you need to determine the pixel count for both the black and white parts of the image. These pixel counts represent the flags hidden within the CTF.

## Participant Achievement:

During the "Technosphere" event organized by FOSS at NSBM Green University, my Capture the Flag (CTF) project drew the attention of enthusiastic participants. In the first part of the CTF, a commendable total of 10 participants demonstrated their logical reasoning and problem-solving prowess by successfully cracking the complex corridor and room-based scenario. Their dedication and ability to decode the hashed values to locate the hidden flag within this portion of the challenge were truly commendable.

However, the pinnacle of achievement in the CTF was reached by a single participant who not only mastered the first part but also delved into the more intricate second segment of the challenge. This extraordinary individual showcased an exceptional level of determination and technical expertise. They undertook the formidable task of decrypting the ctf.exe file and meticulously inspecting the code embedded within it. Deep within the code, I had concealed an enc() function tailored to count the black and white pixels within a given image. This function ingeniously returned the pixel counts, thereby exposing the concealed flags hidden within the image.

The participant's ability to reverse-engineer the CTF.exe file and identify the specific enc() function responsible for extracting the hidden flags was a testament to their technical acumen. This remarkable accomplishment not only highlighted their dedication to solving complex challenges but also illustrated their unbridled curiosity to explore the inner workings of the CTF. In conclusion, this CTF project successfully engaged participants in a captivating cybersecurity challenge, offering a platform for individuals to display their skills and ingenuity. While 10 participants skillfully completed the first part, it was a singular participant's exceptional feat in decrypting the executable and unveiling the flags within the second part that truly exemplified the spirit of exploration and technical excellence within the cybersecurity community. This experience underscores the value of crafting challenges that inspire participants to transcend their limits and approach problems with innovative thinking.

## Summery:
The “Corridor-Pix" CTF challenge, designed exclusively for the "Technosphere" event, offers participants a captivating and intellectually stimulating experience. Comprising two distinct parts, it combines logical reasoning with image analysis, all delivered through the immersive medium of PyQt5-powered GUI. Participants are encouraged to think critically, creatively, and collaboratively, making this challenge an exciting highlight of the event. Prepare to embark on a journey of discovery, unlock the mysteries of the corridor, and reveal hidden flags that await your discerning eye.

When we are talking about my experience in developing this CTF project was a rewarding journey that allowed me to showcase my technical skills, creativity, and dedication. It provided an opportunity to contribute to the cybersecurity community by offering a fun and educational challenge for participants. This project reflects my passion for cybersecurity and software development, and I look forward to creating more engaging experiences in the future.
