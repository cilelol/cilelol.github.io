# ePortfolio
Hello, my name is Kyle Simonetti and welcome to my ePortfolio which showcases the skills I have learned throughout my time at SNHU in the Computer Science field. This ePortfolio includes a professional self-assessment, a code review of my original artifact, and the enhancements I have made to this artifact to showcase the additional skills I have learned since making this artifact.
# Self-Assessment
When I started my Computer Science degree at SNHU, I had little knowledge of coding, only knowing the basics of Python through sites such as codecademy, but I knew it was a field I wanted to learn more about and pursue a degree in. Throughout the Computer Science program, I have refined my skills in the field creating projects related to mobile development, OpenGL, SQL, and full-stack development. Although a challenging experience, I have learned a lot to help me in my future career, which is shown by this final project, which combines skills through the many different projects I have created through this course. 
### Team Collaboration
One key strength I have developed throughout the program is collaberating in a team environment. While most of my projects were done individually, I worked together in a team environment to create a game using Unreal Engine 5 in my GAM-305 class and using Bitbucket for version control, which can be found [here](https://bitbucket.org/gam305greenteam/gam-305-green-team-project/). For this project, I was in charge of the UI/UX design, both creating the art and the code for features such as the HP bar and power-up mechanic. Because we had five people working on the project, collaboration was essential in making sure the project was cohesive, especially since each team member was assigned to the team randomly. Each member's strenghts and weaknesses were quickly assessed to fit each person in the proper role. This project strengthened my skills to adapt within the constraints of the team, and to coordinate development across multiple areas of the project. It also strenghtened my skill in version control tools and communication, as sharing a codebase can lead to conflicts in the codebase if communication is not handled properly. 
### Stakeholder Communication
As stockholders may not have a technical background, it is important to be able to communciate properly with them in non-technical way, while still getting important information across. In my CS-250 course on SDLC, I had to study each stage of the lifecycle following a Scrum-Agile development approach from the perspective of a product owner, scrum master, developer, and tester. This course helped me to understand how stakeholders work together to stay aligned with how users and clients expect the software or application will function. When requirements were unclear, testers would reach out to the project manager for clarification on certain features, which would then be corrected and refined to remain in-line with the requirements. This excercise srengthened my ability to ask clarifying questions and interpret requirements, as well as the importance of open communication, even late in the cycle, to ensure alignment with stakeholder goals. 
### Data Structures and Algorithms
Throughout this program, I my knowledge of data structures and algorithms have grown, allowing me to choose the most efficient option when creating a program. Being effecient with data enables programs to be as efficient as they can be, improving the program's speed and the overall user experience. In my inventory application detailed below, I used the knowledge I have learned over the years to enhance this application to become more efficient and scalable. I have made use of data structures such as HashMaps to efficiently store and retreieve data where data could be easily added with a unique key. In my inventory application, this became important as the size of inventory grows to avoid slowdown. My increased understanding of time and space complexity helped me make better informed decisions on what algorithms would be the most efficient.
### Software Engineering and Database
Throughout this course and my last course in CS-465 Full Stack Development, I had learned how to create a system architecture from the ground up by building a full-stack application that met my clients needs, documentation found [here](CS465SoftwareDesignDocumentTemplate(4).docx). This project integrated frontend and backend components with a database system to store travel information. I gained hands-on experience with creating RESTful APIs, Node.js, Express, Angular, and MongoDB, which all worked together to create an application that handled HTTP requests and responses, seperated concerns between the client-side and server-side functionality, and created a database to store travel data. This experience improved my knowledge significantly in both software engineering and database design, which was vital in enhancing my inventory application. 
### Security
Security is another important area in Computer Science that I have gained knowledge of over the course of this program. Ensuring input is validated and private data is kept private is important in creating a program that is safe, secure, and follows guidelines and policies. Reducing vulnerabilites is also important, and a skill I had enhanced during my CS-305 Software Security class, with my project being available [here](CS305ProjectOneTemplate.pdf). In this course, I learned how to indentify and mitigate security risks such as DoS and injection attacks, used dependancy checks to identify vulnerabilities in outdated frameworks, and created mitigation plans for the client to follow to prevent the found security risks. This experience helped me to better understand the risks associated with systems and how to mitigate them. 
### Course Outcomes
There are five outcomes I had to meet for this course, and these are:
1. Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
2. Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
4. Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
5. Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

Through my enhancement of my warehouse application, I have acheived these outcomes. Course outcome one was accomplished by creating collaborative environments using an API, giving multiple people access to the same information simultaneously as they work on stocking inventory. Course outcome two was accomplished by delivering a UI that is easy to use and understand using minimalistic design and a grid layout that makes it easy to read and view inventory, with documentation and comments that clearly communicate what the code does, and variables names that tell the audience what information they hold. Course outcome three was met by taking advantage of a HashMap for fast lookups, as this is important when inventory starts to become large, as well as HashMaps being perfect for inventory items that each contain uniqeue UPCs. Course outcome four was met by incorporating modern tools such as MVVM architecture, Node.js, Retrofit, and barcode scanning functionality to accomplish industry specific goals in retail. Lastly, course outcome five was met by ensuring data is secure through error handling, such as ensuring UPC’s are always unique and that input for these UPC’s are valid.
### Introduction to Artifact
The artifact chosen to enhance, my inventory application created a few years before this update, shows my increased knowledge and understanding throughout this program. Each enhancement shows my improved knowledge in its respective topic, that being software design and engineering, algorithms and data structure, and databases. It demonstrates my ability to improve upon existing software with the increased knowledge I gain through working on different projects. Below you will find my original artifact through the code review conducted before the enhancement, along with the three enhancements made to the application. The artifact I had chosen was my inventory app I made using android studio for CS-360: mobile architecture and programming. This android application allows users to log in to the application using a username and password, which brings them to a screen to track inventory items. Users can add, delete, and change items as they see fit, with notifications sent to their phone when inventory is low. This application was finalized in October of 2025. I had chosen this artifact to enhance as, firstly, it is the project I made that I was most proud of because of its demonstration of a variety of skills. I also picked this artifact because it showcases my skills in making android applications, which  aligns with the career path I am moving towards, that being mobile application development, and it aligns with my current job, this application being something that could enhance our current inventory management.

# Code Review
This [link](https://www.youtube.com/watch?v=lhLLyipFe_U) contains my code review, which has my talking and showing what the original artifact's code and how it fucntioned, the flaws in its design, and how I planned on enhancing this artifact. 
# Enhancement One - Software Design and Engineering
For enhancment one, this artifact was improved by adding a barcode scanner functionality for an easier way to add items, and a restructure of the code for separation of concern by following an MVVM architectural pattern.
### Inventory View Model Code
Below is the view model class that was added for separation of concerns:
```
public class InventoryViewModel extends AndroidViewModel {
    private InventoryRepository repository;

    public InventoryViewModel(@NonNull Application application) {
        super(application);
        repository = InventoryRepository.getInstance(application);
    }

    public InventoryItem getItemByUPC(String UPC) {
        return repository.getItemByUPC(UPC);
    }

    public void addOrUpdateItem(String UPC, String description, int quantity) {
        repository.addOrUpdateItem(UPC, description, quantity);
    }

    public void updateItemQuantity(String UPC, int quantity) {
        repository.updateItemQuantity(UPC, quantity);
    }

    public void deleteItem(String UPC) {
        repository.deleteItem(UPC);
    }

    public void refresh() {
        repository.getItemsFromAPI();
    }

    public void setListener(InventoryRepository.InventoryChangeListener listener) {
        repository.setListener(listener);
    }
}
```
By seperation of concerns, my code became more organized and easily scalable, as new features can be added easier.
### Barcode Functionality
As adding and updating inventory may take a while when dealing with large amounts of inventory, adding barcode functionality would make it easier for workers to add and update inventory with a simple scan of the UPC on an item. below is my code for this functionality, which automatically adds the UPC when adding an item, as opposed to typing out the UPC manually:
```
// Scanner functionality
        barcodeInput.setOnEditorActionListener((v, actionId, event) -> {
            // Scanning a Barcode converts the Barcode to a string, that being our UPC, so we need to get the input from the scanner as text
            String UPC = barcodeInput.getText().toString().trim();
            if (!UPC.isEmpty()) {
                handleScannedBarcode(UPC);
                barcodeInput.setText("");
            }

            return true;
        });
```
### Course Outcome and Experience
The course outcome I planned to meet in Module One was to demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals. I believe I achieved this goal, as my scanner functionality accomplishes industry-specific goals, that being the grocery or retail industry. The scanner function makes it easier for warehouse workers to add items into inventory through a quick scan. Upon enhancing and modyfing this artifact, I have learned a lot. Firstly, I learned how important seperation of concerns is firsthand, as it made it a lot easier to implement the barcode scanner functionality. Secondly, I had no prior knowledge of how barcode scanners worked or what they output, so that was something I learned although it was simpler than I thought it might be. I had some challenges with changing the code base to work with a unique UPC instead of what it was before, that being an integer that auto incremented, but a few failed runs and some bug fixes later, I was able to get everything to work properly. 
# Enhancement Two - Algorithms and Data Structure
For enhancement two, this artifact was the addition of a HashMap for increased efficiency in how data is stored and accessed. In the orignal version of my artifact, inventory items were stored and accessed using a list, which starts to become inefficient with large amounts of inventory. Because HashMaps use a key:value pair, it made sense to use this data structure, as lookups are fast and each inventory item would have a unique UPC, making it perfect for storing in a HashMap. Going from O(n) to O(1) when needing to display an item makes it so workers are not bogged down by the inefficiency of the program. In my lookup operation shown below, item's can be looked up directly without the need for iteration. 
```
    // Gets an item that matches the UPC
    public InventoryItem getItemByUPC(String UPC) {
        return inventoryMap.get(UPC);
    }
```
Not only is looking up an item more efficient, but adding, updating, and deleting items also become more efficient:
```
if (inventoryMap.containsKey(UPC)) {
            // If the item exists in the database, update the item
            apiService.updateItem(UPC, item).enqueue(new Callback<Void>() {
                @Override
                public void onResponse(Call<Void> call, Response<Void> response) {
                    inventoryMap.put(UPC, item);
                    notifyChange();
                }
```
In this code snippet in my add and update item function, the application can quickly decern if an item exists in the database, and add or update the item accordingly without having to iterate through the inventory.
### Course Outcome and Experience
With this enhancement, I have met course outcome three, as I was able to use algorithmic principles to solve the problem of efficiency in looking up and displaying inventory. I was also able to acheive course outcomes five and two through input validation, error handling, and proper comments. As I was creating this enhancement, I had issues changing a lot of my code to work with the new HashMap, as their was a lot to change and it was easy to forget what still needed to be reworked. I also had to change my repository to a singleton, as after changing to use a HashMap, I found out on creating the repository each time, it created two separate HashMaps in my InventoryActivity and my ItemDetailsActivity since each activity created its own repository.  
# Enhancment Three - Databases
