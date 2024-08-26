## Overview

This project involves the analysis of mobile phone data to extract meaningful insights and perform tasks such as clustering and regression modeling. The dataset contains information about various mobile phones, including their battery capacity, camera specifications, display size, memory, price, processor, ratings, and reviews.

## Features

- **Data Cleaning and Preprocessing:** 
  - Convert text-based fields into numerical values.
  - Extract specific features from complex data strings (e.g., megapixels from camera descriptions).
  
- **Data Visualization:**
  - Visualize the distribution of mobile phone features like price, battery capacity, and ratings.
  
- **Modeling:**
  - Perform clustering or regression analysis to identify patterns or predict outcomes based on the dataset.

## Data

The dataset used for this project is `JDA.csv`, which includes the following features:
- `battery`: Battery capacity in mAh.
- `camera`: Camera specifications.
- `display`: Display size in inches.
- `memory`: RAM and ROM specifications.
- `price`: Price of the mobile phone.
- `processor`: Processor type.
- `rating`: Customer ratings.
- `reviews`: Number of customer reviews.
- `warranty`: Warranty information.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MPranav1/mobile-phone-data-analysis.git
    cd mobile-phone-data-analysis
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebook to see the analysis:
    ```bash
    jupyter notebook Assignment_JDA.ipynb
    ```

## Project Structure

- `Assignment_JDA.ipynb`: Jupyter notebook containing the data analysis, preprocessing, and modeling steps.
- `JDA.csv`: The dataset used in the project.
- `requirements.txt`: List of Python packages required to run the project.

## Usage

This project can be used as a template for analyzing similar datasets or for educational purposes to learn about data preprocessing, visualization, and modeling.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit a pull request or open an issue if you have any suggestions for improvements or if you encounter any bugs.

## Contact

For any inquiries, you can reach out to the project maintainer at [mpranavofficial@gmail.com].
