##  Functional Requirements

The company wants to build a Japanese Learning Application with AI capabilities.

The application will be integrated on the existing Language Portal.

This include the following functionality:

    1. Daily Life Visual Novel Generator - this app will allow the player to visit key locations and have daily routine conversation with variation.

        -It must generate out consistent characters
        -It must maintain chat history of multiple characters


    2. Japanese Text Adventure - this app functionality will slowly introduce Japanese vocabulary , and will contain all primary actions needed to perform writing Japanese.


    3. Japanese Sentence Constructor - this functionality will allow users to input an English phrase and the app will be assisting them in translating it to Japanese without directly providing them the answer.


    4. Sign to Speak - this functionality will allow users to practive ASL finger-spelling via a webcam. The app will present single letter vocabulary and the student will attempt to sign the letter.


    5. Subtitles to Vocabulary - this functionality will take a movie subtitle file and extract all the vocabulary.

        -It will utilize LLM to extract the vocabulary.
        -To ensure lowest cost, an offline batch jobs will be use.
        -Data will be prepared in json structured output
        -Output vocabulary will be evaluated to ensure correctness

    
    5. Speech to Learn - this functionality will allow users to practice speech in a target language. The app will present a single word vocabulary which the student will attempt to speak out.


##  Assumptions

We are assuming that the Open-source LLMs that we choose will be powerful enough to run on hardware with an investment of 10-15k.

We're just going to hook up a single serve in our office to the internet and we should have enough bandwidth to serve the 300 students.


##  Data Strategy

There is a concerned of a copyrighted materials, so we must purchase and supply materials and store them for access in our database.

##  Considerations

We're considering using IBM Granite because its a truley open-source model with training data that is traceable so we can avoid any copyright issues and we are able to know what is going on in the model.

https://huggingface.co/ibm-granite


