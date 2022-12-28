# asl_ios with React
# iOS React Application to Translate the American Sign Language
## by India Daniel

### Note
This version of the translator is non-functional. For the working version, see my other repository: https://github.com/igdaniel-1/ASL_Translate_Swift

### Context
Learning and Translating American Sign Language poses a new challenge that traditional text-based translators have yet to encounter: a 3-dimensional form of input. Those who use American Sign Language, or ASL, to communicate rely on a combination of hand shapes and hand movements. Current transla- tion services, such as print dictionaries or Google Translate, aren’t equipped to handle these extra parameters.
With this in mind, I propose a new format of translation designed specifically for ASL users. This translator would take input through an infrared camera in order to capture the relative positions of the user’s hands to the camera. For output, the user should be able to translate their hand signs to both text and speech. By incorporating a screen where the user’s signs will appear in text format, and a ”text-to-speech” option, ASL users will be able to broaden their communication horizons.


### Objectives
The completed translator will take the form of an iOS application. This appli- cation will use the front and back camera of an iPhone to capture the user’s hand signs as input. While the user is signing, or performing ASL hand signs, the application will compare the real-time positions of their fingers to the ap- plication’s hand sign database. Once the best match is determined, the app’s display will show the corresponding letter/word in the ”Output” window. This window will be able to hold multiple translations at a time. For example, if I were to sign my name letter-by-letter into the translator, the output window would first show the ”I”, followed by the ”N”, and so forth until the output window reads ”INDIA”.

Once a user is done signing the word/phrase, they can click a ”text-to- speech” button next to the output window. This will cause the app to read out the text which came from the hand sign input. By the end of this cycle, an ASL user will be able to communicate via text or verbally to a person who doesn’t understand ASL.

1. Build an iOS application modelled off of my pre-existing ASL Visualizer.
2. Use online iPhone hand detection software to use the phone’s infrared camera to detect hand positioning.
3. Use a MongoDB database to store relative hand positions for each let- ter/simple word.
4. Build an application interface that is modelled off of my pre-existing ASL visualizer.
5. Create an algorithm that maps user input to it’s closest match in the MDB and returns that match.
6. Addoutputfeaturessuchasthe”outputwindow”andthe”text-to-speech” button.
7. If there’s time: Add an ”input text” window to the app in order for non- ASL-using user’s to communicate back to the ASL user.

### Results
This forumlation of my application was not a success. However, if you would like to see the working ASL Translator app, it is available here through my github: https://github.com/igdaniel-1/ASL_Translate_Swift.


### Usage
Use `ionic serve` in the image-gallery/ directory to start the application.
