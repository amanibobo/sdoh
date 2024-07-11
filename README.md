for myself, remeber to download conda on my main computer and also use onedrive to access NOTEEVENTS file if needed.

Other Stuff: 

## Project Title:

Creating a High Quality Synthetic Dataset with Annotated Social Determinants of Health Using Data Engineering

## (Original) Project Description:

This project proposes a comprehensive approach to data engineering, focusing on the extraction and refinement of social determinants of health (SDOH) from clinical notes to create a robust dataset for language model optimization. Utilizing ICEHAMMER (GTRI’s unclassified high-performance computing cluster), the student will employ Python to create synthetic datasets with annotated social determinants of health data. The objective is to iteratively create these datasets to produce a high-quality dataset to be used for language model fine-tuning downstream. The student will be introduced to the process of data engineering, encompassing the extraction, cleaning, and annotation of data. The student will learn the technical skills necessary for handling complex datasets, as well as best practices in data engineering. By the end of the project, the student will have contributed to the development of a high-quality dataset, ready for language model fine-tuning, and gained experience in the field of data engineering. There will no special training required for the student and the student will use a basic computer to complete these tasks.

<br>

- rejection sampling
- When I finish with the generation send it to Andy through box and I he will annotate / do labeling.
- I can use any model to do the generation whether that be open ai or through something else like hugging face doesn’t mater.
- I can also use library’s like faker if I want to
- Only focus on social history for this project because it’s easier
- Other than years and maybe some other numerical stuff, the goal is to replace the chunks like [**lastname 16228**] with something like <LASTNAME: JOHNSON> or just real values to make it apparent what that chunk is

- Generate the notes in simialr strucute to the ones in the mimic dataset. After generating these nots synthetically, have another function that takes in the newly generated data and then does the replacements and keeps json structure
- When generating maybe save it to csv that has a structure of before and after or something simialr
