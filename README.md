# KICa - KAN Imagery Catalog - Documentation

## TOC

- [KICa - KAN Imagery Catalog - Documentation](#kica---kan-imagery-catalog---documentation)
   * [Contributing to the Documentation](#contributing-to-the-documentation)
      + [Prerequisites using Linux Terminal](#prerequisites-using-linux-terminal)
         - [Contributing Process](#contributing-process)
      + [Prerequisites using Docker Compose](#prerequisites-using-docker-compose)
         - [Contributing Process](#contributing-process-1)
   * [Review and Acceptance](#review-and-acceptance)

----------

## Contributing to the Documentation

If you would like to contribute to the documentation , you can follow these steps:

### Prerequisites using Linux Terminal

Before contributing, ensure that you have the necessary tools and dependencies set up on your system.

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Kan-T-IT/QGIS-KICa-Doc.git
   ```

2. Set up a virtual environment and install the required dependencies:

   ```bash
   virtualenv -p python3.10 env3
   source env3/bin/activate
   pip install mkdocs-material
   ```

#### Contributing Process

Once you have the environment configured, you can start contributing to the documentation.

1. Navigate to the project directory:

   ```bash
   cd QGIS-imagery-catalogue-usage-guide
   ```

2. Make the desired changes to the documentation using your preferred text editor.

3. Preview your changes locally by running:

   ```bash
   mkdocs serve
   ```

   This command will start a local server that allows you to view the documentation with your changes in your web browser. The server will provide you with a local URL (usually http://127.0.0.1:8000) to access the documentation.

4. Review your changes in the browser to ensure they look as expected. Make any necessary adjustments.

5. Once you are satisfied with your changes, commit your edits to your local Git repository:

   ```bash
   git add .
   git commit -m "Added/Updated documentation on [Your Contribution]"
   ```

6. Push your changes to your fork of the repository:

   ```bash
   git push origin main
   ```

7. Create a pull request (PR) to submit your changes to the original project repository.




### Prerequisites using Docker Compose

Before contributing, make sure you have the necessary tools and dependencies set up on your system.

1. Last version Docker 
2. Last version Docker Compose


#### Contributing Process

Once you have the environment configured, you can begin contributing to the documentation.


1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Kan-T-IT/QGIS-KICa-Doc.git
   ```

2. Navigate to the project directory:

   ```bash
   cd QGIS-imagery-catalogue-usage-guide
   ```

3. Run the following command in the console:

   ```bash
   docker-compose -d up
   ```

4. Make the desired changes to the documentation using your preferred editor.

5. Preview your changes locally by running. The server will provide you with a local URL (usually http://127.0.0.1:8000) to access the documentation.

6. Review your changes in the browser to ensure they look as expected. Make any necessary adjustments.

7. Once you are satisfied with your changes, commit your edits to your local Git repository:

   ```bash
   git add .
   git commit -m "Added/Updated documentation on [Your Contribution]"
   ```

8. Push your changes to your fork of the repository:

   ```bash
   git push origin main
   ```

9. Create a pull request (PR) to submit your changes to the original project repository.


## Review and Acceptance

After you create a pull request, the project maintainers will review your contribution. If everything is in order, they will merge your changes into the main documentation. Thank you for contributing to documentation!!


