# Priority-Task-Selection-Using-Evolutionary-Programming
A web app that utilizes **Evolutionary Programming** to determine and prioritize tasks for efficient scheduling.

## About the Project

This is a program to calculate the tasks that we can prioritize to do by determining them using <b>Evolutionary Programming</b> algorithm. This program is a web-based platform, created with Flask using Python programming language.

## Screenshots
  Dashboard
  :-------------------------:
  ![Screenshots/1.%20Dashboard.png](Screenshots/1.%20Dashboard.png)
  Example Input Values on Forms
  ![Screenshots/2.%20Input%20Form.png](Screenshots/2.%20Input%20Form.png)
  Example Results
  ![Screenshots/3.%20Result.png](Screenshots/3.%20Result.png)

## Live Demo
Web App **Priority Task Selection Using Evolutionary Programming**: [http://xxx.xxx](http://xxx.xxx)

## Technology Used
* HTML
* CSS
* Javascript
* Python
* Numpy
* Flask
* Evolutionary Programming

## Installation

1. Clone this repo
   ```sh
   git clone https://github.com/LinggarM/Priority-Task-Selection-Using-Evolutionary-Programming
   ```
2. Open the repo folder you have cloned in your PC
3. Create a virtual environment
   ```sh
   python -m venv myenv
   ```
4. Activate the virtual environment
   ```sh
   myenv/Scripts/activate or "myenv/Scripts/activate" (Windows)
   myenv/bin/activate (Linux)
   ```
5. Install the requirements/ dependencies
   ```sh
   pip install -r requirements.txt
   ```

## Usage (Tutorials)

1. Open CMD in Repository Folder
2. Run the web app by executing this command :
   ```
   python app.py
   ```
   or :
   ```
   run Flask
   ```
3. Open the given URL
   ```
   http://127.0.0.1:5000/
   ```
4. There are 5 inputs :

    1. The number of tasks (E.g: 10)
    2. All of the task names (E.g: Food1, Food2, Food3, ..)
    3. All of the priority scales for each task. Range: 1-5, 1 for the lowest prioritize and 5 for the highest prioritize (E.g: 5, 3, 1)
    4. All of the task completion times for each task **in hours**. (E.g: 1, 2, 3)
    5. Total time you have **in hours**. (E.g: 8)

5. Inputs example :
    - First input: 10
    - Second input: Making the bed, Washing the dishes, Washing clothes, Ironing clothes, Mopping the floor, Watering the plants, Bathing the cat, Filling the bathtub, Taking care of the children, Tidying up things
    - Third input: 4, 3, 3, 2, 2, 1, 1, 1, 3, 2
    - Fourth input: 1, 2, 3, 2, 2, 1, 1, 1, 3, 2
    - Fifth input: 8

## Contributors
* [Linggar Maretva Cendani](https://github.com/LinggarM) - [linggarmc@gmail.com](mailto:linggarmc@gmail.com)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments
* [Colorlib](https://colorlib.com/) for HTML templates
* <div style = "color:#FFF">Icons made by <a style = "color:#57b846" href="https://www.freepik.com" title="Freepik">Freepik</a> from <a style = "color:#57b846" href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
