1. # UniErase

   A comprehensive framework for machine unlearning in large language models.

   ## Setup Instructions

   ### 1. Environment Setup

   Set up the environment according to the requirements of both projects:

   - [closer-look-LLM-Unlearning](https://github.com/your-link-to-closer-look-LLM-Unlearning)
   - [EasyEdit](https://github.com/your-link-to-EasyEdit)

   Follow the installation instructions from both repositories to ensure all dependencies are properly installed.

   ### 2. Perform Token-Level Unlearning

   Run the token-level unlearning procedure using the Jupyter notebook:

   ```bash
   jupyter notebook train_UNL.ipynb
   ```

   **Note:** Make sure to update the model path in the notebook before executing.

   ### 3. Perform Unlearning Editing

   Execute the unlearning editing script:

   ```bash
   python run_edit.py
   ```

   ### 4. Evaluate Unlearning Performance

   Run the evaluation script to assess unlearning effectiveness:

   ```bash
   python xxx_eval.py
   ```

   Replace `xxx_eval.py` with the appropriate evaluation script for your specific use case.

   ### 5. Evaluate General Model Ability

   Run utility evaluation to ensure the model's general capabilities are preserved:

   ```bash
   python evaluate_utility.py
   ```

   This step verifies that the unlearning process does not significantly degrade the model's performance on general tasks.
