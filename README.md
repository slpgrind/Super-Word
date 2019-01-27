### Super Word
## Inspiration
Speech and language delays and disorders affect 1 in 12 children in the United States [3] and are considered the “most common disability of childhood, least diagnosed by primary care physicians.” [4] Furthermore, delays in early identification of these conditions can result in delays in treatment, which is crucial for children to develop communication and literacy skills for school readiness and behavioral and mental health.

It is estimated that smart speakers (e.g., Amazon Echo and Google Home) are already in 30 million American homes, and they are used regularly by children and are designed with features specifically for younger users [2]. However, none of the existing voice-enable interaction on these smart speakers is capable of detecting and assessing children's early speech development, despite its ubiquitous computing power for automatic speech recognition.

## What it does
"Super Word" is an Alexa quiz game for children age 4+ to play at home independently. This game provides a sound effect, a question, or a brief description for the child to guess 48 words that cover all phonemes in English [1] across multiple categories (e.g., nouns, actions, and adjectives). By using the Amazon automatic speech recognition to process the child's pronunciation during the gameplay experience, "Super Word" provides a preliminary screening of a child’s speech production in order to determine whether the child’s speech development is on track. This information can be extremely crucial for both parents and healthcare providers (e.g., pediatricians).

## How we built it
We first identified our user group and a list of vocabulary content from prior research, and then wrote the scripts and added associated sound effects from the [Amazon Sound Library](https://developer.amazon.com/docs/custom-skills/ask-soundlibrary.html). By following tutorials on [Alexa Skills Kit](https://developer.amazon.com/alexa-skills-kit), we integrated the front-end voice user interface with the back-end Amazon Lambda service.

## Challenges we ran into
- One of our team-mates was out for exam most of the second day, but our team caught up by the end; 
- It was difficult to connect the device and integrate front-end & back-end; 
- QA testing took longer than anticipated, required a dedicated quiet environment, and only one computer was able to connect to the [Alexa Skill Testing Tool](http://echosim.io).

## Accomplishments that we're proud of
- Debugging together and supporting each other 
- Successful integration of Amazon Lambda with the front-end voice user interface

## What we learned
- Explore all available assets in the library carefully first (e.g., sound library) and define the correct genre of game (e.g., quiz game vs. trivia game)
- Ensuring device compatibility and network stability is crucially important for designing for IoT
- Teamwork makes dreamwork and everyone can code and/or contribute

## What's next for Guess The Word
- We plan to keep working on it and hopefully conduct some user testing with children 
- We plan to submit a final prototype to the Student Research Competition at an upcoming conference

## References
[1] Brackenbury, T., Zickar, M. J., Munson, B., & Storkel, H. L. (2017). Applying Item Response Theory to the Development of a Screening Adaptation of the Goldman-Fristoe Test of Articulation–Second Edition. *Journal of Speech, Language, and Hearing Research*, *60*(9), 2672-2679.

[2] Cheng, Y., Yen, K., Chen, Y., Chen, S., & Hiniker, A. (2018). Why Doesn’t It Work? Voice-Driven Interfaces and Young Children’s Communication Repair Strategies. In *Proceedings of the 17th ACM Conference on Interaction Design and Children* (pp. 337-348). ACM.

[3] Prelock, P. A., Hutchins, T., & Glascoe, F. P. (2008). Speech-language impairment: how to identify the most common and least diagnosed disability of childhood. *The Medscape Journal of Medicine*, *10*(6), 136.

[4] Wallace, I. F., Berkman, N. D., Watson, L. R., Coyne-Beasley, T., Wood, C. T., Cullen, K., & Lohr, K. N. (2015). Screening for speech and language delay in children 5 years old and younger: a systematic review. *Pediatrics*, peds-2014.
