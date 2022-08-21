# CS-230
#### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room is a client who is looking to develop their application "Draw it or Lose it" for multiple web platforms to expand their market and user base. Draw it or lose it is a game where teams compete to guess what image is being drawn. The application will render an image within 30 seconds and the team will need to guess what is being rendered within that 30-second period, otherwise the opposing team will have the opportunity to guess.

#### What did you do particularly well in developing this documentation?
In developing the documentation, I felt that my strength was considering the overall architecture and data flow. I feel it is incredibly important to understand the data flow and the pros and cons of decisions in managing your data. By taking a hybrid approach to security storing persistent long term data securely on cloud servers, we are able to create a scaling solution that can help the team grow their user base without the prohibitive costs and risk of creating their own network infrastructure and managing it in house.

#### What about the process of working through a design document did you find helpful when developing the code?
While developing the code, I found that the design documentation was incredibly helpful in understanding the exact user requirements. By having a clear and concrete outline of user requirements, you are able to weigh your technical options before implementation. This allows for a more efficient workflow as you you will be less likely to need to refactor because of misunderstood requirements.

#### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could pick one part of the document to revise, it would be the evaluation table. I feel that while there was valuable information included, I would have liked to further break down each section to give a clearer picture of each item within the table. The simple summaries that I initially included could potentially be misunderstood or need further evaluation which wouldn't be very valuable to the client.

#### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I interpreted the user's needs by breaking down each part of the application by feature and further breaking down each part of the feature into smaller atomic parts. This helped me be able to weight technical decisions such as storage and how data might need to be handled. For example, by knowing that users expect to have a database of images that players would need to guess, I came to the decision of S3 storage as it is secure and scalable so that the developers can continue to add and maintain their image database without users being able to cheat and locally access files.

#### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
The most important approach is breaking down user specifications as much as possible. This allows you to slice the technical work into small iterative chunks that are easily testable and can be further iterated on as requirements change. It's also important to keep the initial architecture fairly loose to accommodate potentially changing requirements so that you can change course without major refactors or redesigns.
