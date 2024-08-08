![Manim Logo](https://www.manim.community/)

# Manim Animations

Welcome to my Manim Animations repository! This repository is where I store all my Manim code, including projects I'm working on as I learn, as well as future production-ready animations illustrating concepts in Mathematics, Science, and Computer Science.

## About This Repository

This repository serves as both a learning space and a production environment for creating programmatic animations using [Manim](https://github.com/3b1b/manim), the mathematical animation engine created by 3Blue1Brown. Here, you'll find scripts and project files that demonstrate various mathematical, scientific, and computer science concepts in a visually engaging way.

## Structure

The repository is organized into the following sections:

- **Learning**: Contains all my experimental and learning scripts as I explore Manim's capabilities. These scripts may include:
  - Basic shapes and transformations
  - Algebraic and geometric visualizations
  - Simulations of mathematical concepts like calculus, linear algebra, etc.
  - Introductory tutorials and notes
  
- **Projects**: Contains completed and polished animations intended for sharing or publishing. Each project will typically have its own folder with:
  - `main.py` or equivalent script file
  - Any custom modules or utilities
  - Project-specific assets (like images, sounds, etc.)
  - Rendered video outputs (where applicable)
  
- **Assets**: A centralized folder for shared resources across multiple projects, such as:
  - Images, SVGs, or other graphics
  - Audio files
  - Custom animations or effects

- **Documentation**: Detailed documentation for more complex projects, including:
  - Concept explanations
  - Mathematical proofs or derivations
  - Links to relevant resources or references

  (If any of these seems to be missing, you found my repo too soon and I'm still working on it! :smiling_face_with_tear:)

## Installation & Setup

To run the code in this repository, you'll need to install Manim and its dependencies. Below are the basic setup instructions:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/skipperr254/manim.git
   cd your-repo-name
   ```

2. **Set Up Python Environment**:
   Ensure you have Python 3.8 or later installed. You can use `virtualenv` or `conda` for managing your Python environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Manim and Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Running Manim Scripts**:
   You can run a Manim script using the following command:
   ```bash
   manim -pql your_script.py
   ```
   - `-pql` flags: 
     - `p`: preview after rendering
     - `q`: render at low quality
     - `l`: fast rendering

   For more options, refer to the [Manim documentation](https://docs.manim.community/en/stable/).

## Contributing

This repository is a personal learning project, but I'm open to contributions, suggestions, or ideas. If you have something to add, feel free to fork the repository and submit a pull request.

## License

This repository is licensed under the MIT License. Feel free to use, modify, and distribute the code as you see fit.

## Acknowledgements

- **Manim**: Thanks to [3Blue1Brown](https://www.3blue1brown.com/) for creating Manim and making mathematical visualizations accessible and beautiful.
- **Community**: Special thanks to the Manim community and all contributors who have helped improve and expand the software.

---