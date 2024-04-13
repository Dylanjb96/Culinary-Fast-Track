### Culinary Fast Track:
The purpose of our website is to provide a comprehensive platform for food enthusiasts, home cooks, and culinary adventurers to explore, discover, and share a wide variety of delicious recipes. Whether you're a seasoned chef looking for inspiration, a novice cook eager to learn new skills, or simply someone who loves to experiment with flavors in the kitchen, our website aims to cater to your culinary interests and aspirations.

### What You Can Do On The Website:

- **Browse Recipes**: Explore our extensive collection of recipes spanning various cuisines, cooking techniques, and dietary preferences.
- **Discover New Flavors**: Dive into a world of flavors and ingredients, from classic comfort foods to innovative culinary creations.
- **Get Inspired**: Find inspiration for your next meal, party, or special occasion with our curated selection of recipes and cooking tips.
- **Share Your Creations**: Share your culinary masterpieces with the community by adding your recipes.


### How to Run The Website: Culinary Fast Track:

1. **Enter Virtual Environment**:
   - Step 1: Create a folder and open it in visual studio code.
   
  - Step 2: open a new terminal in VS code and run this command to create a virtual environment:
    ```
    > py -3 -m venv .venv
    ```
   
   - Step 3: Activate the virtual environment using the following command:
     ```
     > .venv\scripts\activate
     ```
     - Step 4: now go to --view -- command palette -- type Select Python Interpreter, from the list --select the virtual environment in your project folder that starts with ./.venv or .\.venv:
     
     - Step 5: Open a new terminal that will activate the newly created virtual environment.
     
     - Step 6: run the following command in the terminal:
       ```
       > python -m pip install --upgrade pip
       ```
     
     - Step 7: Install Flask in the virtual environment-run following command -
       ```
       > python -m pip install flask
       ```

3. **Start Server**:
   - Run the Flask application server with the following command:
     ```
     > python app.py
     ```

4. **Access the Website**:
   - Open your web browser and navigate to [http://127.0.0.1:6688](http://127.0.0.1:6688) to view the website.
  
5. **Uploading it on Render.com**
   - Before uploading it on the Web Service, You have to create a requirment file You can create this file manually or by using the
   - ```
     > pip freeze > requirements.txt
     ```
      command in your terminal after activating your virtual environment (if you're using one).

     Ensure that host='0.0.0.0' is in the code as Render wont be able to build and put the website live.
     
      if __name__ == '__main__':
    app.run(debug=True, host='0.0.0.0', port=6688)


### Visit the Wesbite
Once the server is running, you can explore the features and functionalities of Culinary Fast Track by browsing to the provided URL below:
https://culinary-fast-track.onrender.com/
