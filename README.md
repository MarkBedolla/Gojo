# Gojo
This project provides a drawing of Gojo a character from the anime show Jujutsu Kaisen using only 3 lines of code.

**Getting Started**

1. **Installation:**
   
   - Go down to search bar and open 'Terminal' and run this command:
   ```bash
   pip install sketchpy
   ```

2. **Verify the Installation:**

   - After installation, check if sketchpy is installed correctly by running:
   ```bash
   python -c "import sketchpy; print(sketchpy.__version__)"
   ```

3. **Run a Sketchpy Example:**
   - To test it, open a Python script or interactive shell and try:
     ```bash
     from sketchpy import library
     
     obj = library.rdj()
     obj.draw()
     ```
4. **Any issues or troubleshooting:**
   - If you get a ModuleNotFoundError like i did while setting up this project, make sure you are using the correct Python environment.

    -  If needed upgrade pip:
   ```bash
   pip install --upgrade pip
   ```
   - If installation fails, try:
   ```bash
   pip install --no-cache-dir sketchpy
   ```
6. **Gojo drawing:**
   - After making sure everything works you are ready to type 3 lines of code to make a drawing of Gojo.
   ```bash
   from sketchpy import library as lib
    obj = lib.gojo()

    # Draws the image of gojo
    obj.draw()
   ```
   **Still confused?**
   - Try watching this step-to-step video on how to download Sketchpy: https://youtu.be/WXv3_LwmR2Q?si=cQJrAyb_khWDWz-3


   **Screenshot:**
   
   ![image alt](https://github.com/MarkBedolla/Gojo/blob/947a6f8d040512ae206a9034bf70e15aef723e4d/Gojo.png)
     

