
# **To-Do List Application**

## **Overview**

This **To-Do List Application** is a responsive, user-friendly task management tool built using **React**, **JavaScript**, **HTML**, and **CSS**. I built it with the goal in mind to do interactive front-end applications with modern web technologies, and functional programming principles.

The app provides core functionalities to help users effectively organize their tasks:

* **Add Tasks**: Easily add new items to your to-do list.  
* **Delete Tasks**: Remove tasks with a single click.  
* **Reorder Tasks**: Move tasks up or down in the list to adjust priorities dynamically.

This project showcases skills in:

* **React Hooks**: Leveraging `useState` to manage and manipulate application state.  
* **Dynamic Rendering**: Efficiently updating the UI based on user interactions.  
* **Event Handling**: Capturing user input and implementing interactive features.  
* **Array Manipulation**: Using array methods like `filter`, `map`, and array destructuring for optimal state updates.

## **Features**

1. **Task Management**: Add, delete, and reorder tasks to prioritize activities effectively.  
2. **Responsive Design**: Ensures compatibility with various devices and screen sizes.  
3. **Intuitive UI**: A clean and simple design that makes task management effortless.

## **Technologies Used**

* **React**: For building reusable and interactive components.  
* **JavaScript (ES6+)**: For logic and interactivity.  
* **HTML5**: For semantic structure.  
* **CSS3**: For styling and layout.

## **Code Highlights**

Key components of the application include:

**Dynamic Task Updates**: Updating the state with React’s `useState`:  
function addTask() {  
    if (newTask.trim() \!== "") {  
        setTasks(prevTasks \=\> \[...prevTasks, newTask\]);  
        setNewTask("");  
    }

* }

**Reordering Tasks**: Leveraging array destructuring to swap task positions:  
function moveTaskUp(index) {  
    if (index \> 0\) {  
        const updatedTasks \= \[...tasks\];  
        \[updatedTasks\[index\], updatedTasks\[index \- 1\]\] \= \[updatedTasks\[index \- 1\], updatedTasks\[index\]\];  
        setTasks(updatedTasks);  
    }

* }

## **How to Run**

1. Clone this repository:  
   git clone \<repository\_url\>  
2. Navigate to the project directory:  
   cd todo-list-app  
3. Install dependencies:  
   npm install  
4. Start the development server:  
   npm start  
5. Open your browser and navigate to `http://localhost:3000`.

## **Future Enhancements**

* Add support for task deadlines and reminders.  
* Implement drag-and-drop functionality for reordering tasks.  
* Enhance styling with animations and themes.

