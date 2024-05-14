# Fishing-Master  

Survey: <https://forms.office.com/e/v7PNbS4esb>  

Demo Video: [FishingMaster\_demo.mp4](https://cf-my.sharepoint.com/:v:/g/personal/chenn16_cardiff_ac_uk/ETsrJAWjhy1DmnRosLE7RgIBWJKH-IGPMcDvEutBlOs7vQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0\&e=cREC6w)  


**PART 1: PROTOTYPING**
 

**App Name:** Fishing Master

 

**Introduction:** A mobile fishing game application for blind and speech-disabled individuals using MIT APP Inventor.

 

**Features:**

Our application features are customized and optimized for blind and speech-disabled users to ensure our target users can fully experience and enjoy our game.

 

**Voice Navigation:**

The application provides voice navigation to guide users in simulating fishing activities in the game.

 

**Game Sound Effects:**

The application offers rich sound effects, such as ocean background music, fish biting sounds, game progression sounds, and victory/failure sounds.

 

**Tactile Feedback:**

The application provides tactile feedback, such as vibration or sound prompts, to help users perceive changes in the game.

 

**Simple Operation:**

Design simple and understandable operation functions, allowing activities like fishing to be completed through actions like shaking the phone.

 

**Challenge:**

Simulate real fishing processes through bait consumption (feedback to the user via voice prompts), judgment based on fish size and hook size when reeling in, increasing game challenge and fun.

**Gameplay:**

*   Users understand the operation instructions through voice navigation and simulate fishing actions with voice commands.

*   Complete fishing processes through simple operations like casting and reeling.

*   Tilt the phone to move the bait. When a fish bites the hook, the phone vibrates to provide feedback to the user about the fish biting, and reeling in can be done by shaking the phone.

*   When successfully catching a fish, the game verbally announces the current score and chance.

*   When catching 5 fish (5 points), the game progresses, the bait size increases, more fish species can be caught, and new fish species are unlocked.

*   When catching 10 fish (10 points), the game is won.

*   Chance decreases by one when catching a fish larger than the hook size. When chance reaches 0, the game failed.

**Future Development Features:**

*   Provide fishing knowledge learning mode to help users understand fishing techniques, fish species knowledge, and other related content.

*   Optimize the progression feature, unlocking more fish species.

*   Simulate the casting process using motion sensors.

*   The application should provide clear and concise voice instructions to guide users through different game activities, such as selecting fishing locations and equipment.

*   Provide a learning mode to help users understand fishing techniques, fish species knowledge, and other related content.

To elaborate on the user experience (UX) principles involved in integrating good usability decisions in "Fishing Master", we will focus on the following key aspects:

1.  **Accessibility for Blind and Speech Users:** UX design prioritizes accessibility to ensure that blind and speech-disabled users can easily navigate and interact with the application. This includes features such as voice navigation, tactile feedback, and simple operations to accommodate users who rely on auditory and tactile cues rather than visual feedback. For example, the voice prompt feature at the start of the game is designed for user interaction using the Accelerometer Sensor and TextToSpeech functions, making it convenient for users, especially blind and speech-disabled users, to initiate the game and understand the game process, mechanics, and gameplay methods.

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

2.  **Clear and Intuitive Functionality and Interface Design:** The interface design aims to provide clear and intuitive navigation, allowing users to easily understand the structure of the application and access its various functions, such as using simple gesture operations (vibration) and listening to voice instructions to complete fishing activities. This seamless guidance leads users through the game experience.
3.  **Feedback and Guidance:** UX design incorporates feedback mechanisms to provide users with clear guidance and feedback throughout their interaction with the application. This includes audio prompts, tactile feedback, to inform users of their actions, progress, and any relevant game events. For example, the vibration feedback mechanism when the bait touches the fish, we add vibration sounds to alert the user so that they can respond accordingly through the vibration feedback of their hands (shaking the phone to fish).

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

And the feedback sound when successfully catching a fish (providing feedback on the user's current score and remaining chances), making it easy for users to track their progress in the game.

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

 

4.  **Sensory Engagement:** The application aims to engage users through multiple sensory channels, enhancing the overall user experience. This includes immersive audio effects such as ocean background music and realistic sound effects for fishing actions, creating a more appealing and enjoyable experience for visually impaired users. Additionally, tactile feedback further enhances immersion and interaction within the game.

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

The sound effects of the fish biting the hook, game progression, and game success or failure.

 

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

 

**Considerations for general applicability and user breadth**

To accommodate a wider range of users, we have provided additional gameplay options for general users (such as using buttons to move the bait and trigger fishing) and viewing buttons during the current game process. However, these features are only alternative options and not essential core functions required for running the game, so they do not affect our main target audience of visually impaired and speech-disabled users playing the game.

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

 

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)

 

![转存失败，建议直接上传图片文件](<转存失败，建议直接上传图片文件 >)


**PART 2: REQUIREMENTS**

**2.1 Stakeholders**

 

**2.1.1. Blindness and Speech**

**Description**

*   The primary stakeholders of the game. They are the target users who directly benefit from the application's customized functionalities.

*   Individuals with dual disabilities of blindness and speech impairment, unable to engage in game interaction and communication through traditional means.

*   They may rely on assistive technologies and devices, such as voice navigation and tactile interaction, to help them understand game content and perform operations.

 

**2.1.2. General Users (Non-disabled individuals)**

**Description**

*   General users have normal visual and language abilities, enabling interaction through sight and speech.

*   They require a game application with rich content and engaging features that can provide an entertaining and relaxing fishing experience.

 

**2.2 Reasons for Target User Selection**

**2.2.1 Individuals with Dual Disabilities (Blind and Speech)**

Individuals with dual disabilities seek a game application that allows interaction through sound and touch, enabling them to experience the joy of fishing and participate in a virtual world.

Adults with congenital blindness show increased activation in brain areas associated with language during speech comprehension, including the visual cortex, with activation varying based on syntactic difficulty and semantic content (Röder et al., 2002). Individuals with dual disabilities face challenges related to vision and speech and require an application that is simple to navigate, easy to operate, and provides assistance through voice navigation and tactile feedback to help them understand game situations and complete tasks. They also desire applications that offer educational content to learn about fishing knowledge and skills while being entertained.

Accessible digital games are important for players (with or without disabilities) to experience social connections, escapism, and artistic experiences, while also enabling them to feel capable and on equal footing with non-disabled players (Cairns et al., 2019). Selecting blind and speech-impaired users as target users reflects the developers' concern for social responsibility and inclusivity. This choice is not only driven by commercial considerations but more importantly to meet the needs of disabled individuals and help them better integrate into society and enjoy life.

Disabled gamers often face difficulties when playing most games. This segment of the gaming population is largely overlooked (Khaliq & Torre, 2019). Blind and speech-impaired users, as a relatively small but still important user group, are often overlooked or their needs are not fully met. Therefore, developing applications for this user group may provide developers with a competitive advantage in the highly competitive gaming application market, especially in the gaming application market.

 

**2.2.2 General Users**

While our application's primary target users are individuals with blindness and speech impairments, we also recognize the need for the application to cater to general users (non-disabled individuals).

These stakeholders are chosen because they are directly affected by the development of the gaming application, and their needs and feedback will directly influence the quality and user experience of the final product. By considering the needs of general users, we can design more diverse and attractive features, thereby enhancing the user experience of the application.

 

**2.3 Persona of one stakeholder**

**Persona:** Emilia - Individual with blind and speech impairments

**Demographics**:

*   Age: 30 years old
*   Occupation: Freelancer

**Interests**: Emilia enjoys outdoor activities and experiencing new things. She particularly loves the sea and is interested in fishing.

**Skills**: Proficient in using voice navigation and tactile interaction devices. She can adeptly use both smartphones and computers.

**Frustrations**: Emilia, being someone with dual sensory impairments, yearns to experience the joy of fishing. However, due to her visual and speech impairments, she cannot participate in traditional fishing activities.

**Needs**: She hopes for a gaming application that allows interaction through sound and tactile feedback, enabling her to experience the pleasure of fishing in a virtual world. Additionally, she desires the application to provide educational content, allowing her to learn about fishing knowledge and techniques while being entertained.

 

**2.4 Functional requirements**

 

**Voice Navigation (MVP):**

Users should be able to navigate the application through voice commands.

The application should provide clear and concise voice instructions to guide users through various fishing activities.

 

**Tactile Feedback (MVP):**

The application should provide tactile feedback for blind users to perceive game events and changes.

Implement tactile feedback mechanisms such as vibration or sound alerts to indicate events such as catching fish or changes in fishing conditions.

 

**Game Sound Effects (MVP):**

Rich sound effects such as ocean background music, fish biting sounds, and victory/failure prompts enhance the gaming experience.

 

**Challenge Mechanism (MVP):**

By simulating real fishing processes, including factors such as bait consumption, fish size, and hook size, increase the challenge and fun of the game.

**Simple Operation Interface:**

Design an intuitive and user-friendly interface suitable for both blind and non-blind users.

Support simple gesture commands to complete fishing activities such as casting and reeling.

 

**Minimum Viable Product (MVP) Functional Requirements:**

*   Voice Navigation

*   Tactile Feedback

*   Game Sound Effects

*   Challenge Mechanism

These four key requirements are essential for a basic yet fully functional experience for both blind and sighted users. They allow navigation, feedback on game events, and active participation in fishing.

 

Voice navigation is crucial for blind and speech-impaired users to navigate and interact with the game. Without it, understanding game rules and engaging in fishing would be difficult.

Tactile feedback helps blind and speech-impaired users perceive game changes through vibration or sound prompts, enhancing their experience.

Game sound effects add enjoyment and realism, immersing users in the game. They're vital for blind and speech-impaired users to perceive the environment and actions, enhancing appeal and entertainment.

The challenge mechanism boosts playability and long-term engagement, making the game more appealing. Without it, the game becomes monotonous, reducing enthusiasm and engagement.

**2.5 Non-functional requirements**

 

**Accessibility (MVP):**

For blind and speech users, the application interface must support voice navigation, tactile feedback, and simple operation to meet their special needs.

For other regular users, the application interface should remain clear and intuitive while ensuring it does not compromise the usability for blind and speech users.

 

**Performance (MVP):**

The application must have good performance to ensure quick response to user actions and requests.

For blind and speech users, optimizing application performance is particularly important to ensure smooth voice navigation and tactile feedback.

 

**Reliability (MVP):**

The application must be stable and reliable, with minimal crashes or errors.

Especially for blind and speech users, application stability is crucial to avoid frustration and setbacks.

 

**Security (MVP):**

The application must ensure the security of user data and privacy, preventing unauthorized access and attacks.

For blind and speech users, they may be more sensitive to application data and more susceptible to having information accessed and exposed without their knowledge. They may rely more on the application to store personal information, making security particularly important.

**Usability (MVP):**

The application must provide a simple and user-friendly interface to ensure all users can easily understand and operate it.

For blind and speech users, interface design should consider their special needs, such as sensitive vibration sensors and clear voice instructions.

For other regular users, interface design should remain friendly and intuitive.

**Compatibility:**

The application must be compatible with different devices and operating systems, including different versions of operating systems (due to the limitations of MIT App Inventor, some features such as vibration may not work properly on Android devices).

 

**2.6 Data requirements**

**Game State Data (MVP):**

*   **Requirement Description:** The application needs to store user's game state data, including scores, achievements, and unlocked features, to personalize the user's gaming experience and provide feedback.

*   **Data Sources:** User's gaming actions and interactions, as well as internal game settings.

*   **Analysis:** Game state data is crucial for all users, but it's especially essential for blind and speech-disabled users. These data will help them understand the progress of the game and make appropriate adjustments and responses. For example, the application can notify users of hooked fish status through sound prompts or tactile feedback.
