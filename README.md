# Specialisation-Assessment
## CFG Specialisation Assessment Theory Questions

1. **In design heuristics, what does the term “advantages of Matching between system and the real world” mean? What are the advantages?**
    1. ‘Match between the System and the Real World’ is one of Nielsen’s ten principles of general design. This suggests that a system should share the same language, concepts and actions as the user, rather than the user having to learn a new language to understand the system.
        1. An advantage of this is reduced mental load. A user is able to use a system that they already understand better than one they don’t because they can predict the system’s behaviour.
        2. Another advantage of this is a reduction in errors. A user is much less likely to make mistakes on a system that’s easier to understand than on a complicated system.
        3. A final advantage is improved user efficiency. A system that is easy to understand is also faster to navigate because the user spends less time figuring out what things do.
    
2. **What do you understand by “Single source of truth”? and how does it relate to redux? What are the advantages ?**
    1. A single source of truth is the idea that every element of data is collected and referenced from a single location ‘the source’. In regards to Redux, there is a similar principle because the state of the entire application is maintained in a global store, which is the ‘single source of truth’ for the application.
        1. An advantage of this is consistency. For example in a social media app, if the state ‘isLoggedIn’ is maintained in the store, all components and pages are able to fetch this same state leading to consistency across the app. Switching from one page to another won’t log a user out because the state is maintained.
        2. Another advantage is collaboration. Because there is a single store, team members can collaborate more effectively, as everyone is working with the same data, which reduces the chances of conflicts of inconsistencies.
        3. A final advantage is easy debugging, as there is a single place to inspect and edit the application’s state, making it easier to fix issues with the applications behaviour.
    
3. **What is the difference between a stateless component and a stateful component in React?**
    1. There are two types of components in React; a stateless component, also known as a functional component and, a stateful component also known as a class component.
        1. One difference is that stateless components are written as functions where as stateful components are written as a class
        2. Another difference is that state cannot be added to a functional component (without hooks), whereas state can be added to a class component
        3. Another difference is that a stateless component use props, which are pieces of information contained in objects that get passed to and between the components, whereas a stateful component can have data assigned to it through state, which are like variables that are managed within the component, that trigger re-renders when altered.
    
4. **List out the advantages and disadvantages of exploratory testing (used in Agile) and scripted testing?**
    1. Exploratory Testing is an approach that focuses on the discovery of bugs and defects by the individual tester, whereas Scripted Testing is an approach that focuses on test cases, with detailed tests that follow a set ‘script’
        1. An advantage of exploratory testing over scripted testing is it allows for more flexibility and creativity. Because the testers aren’t following a script, they can explore the application and discover unexpected issues that a script couldn’t account for
        2. Another advantage of exploratory testing over scripted testing is it’s better suited for agile environments where the needs and requirements for the application would constantly change. Scripted testing cannot adapt to evolved software.
        3. A disadvantage of exploratory testing over scripted testing is a lack of documentation. Because the tests are not pre-planned, it may be difficult to verify the test results.
        4. Another disadvantage of exploratory testing over scripted testing is that the testing will only cover what the tester thinks to test. There could be potential bias or blind spots if the tester focuses too much on certain areas.
        5. An advantage of scripted testing over exploratory testing is reproducibility. Because the test cases are pre-defined, the tests are more easily produced and verifiable than exploratory tests.
        6. Another advantage of scripted testing over exploratory testing is consistency. Because the testers are constantly executing the same steps, it reduces the likelihood of human error during testing.
        7. A disadvantage of scripted testing over exploratory testing is time consumption. Creating and maintaining detailed and effective test scripts can be time-consuming, especially in an agile environment where test cases may often be made redundant by new project requirements.
        8. Another disadvantage of scripted testing over exploratory testing is the possibility of late detection. Because it can be time-consuming to create test cases, they may be performed later on in the project’s development cycle, meaning errors may not be discovered until the testing phase has started.
