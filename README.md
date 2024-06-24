# CODETECH-TASK-2-NLP

NAME: ABHINAV KAUSHIK

COMPANY: CODTECH IT SOLUTION

ID: CT08SP1029

DOMAIN: ARTIFICIAL INTELLIGENCE

MENTOR: SRAVANI GOUNI


An overview of the project:

1. **Project Purpose:**
   - Extract and manage chapters from a text file containing a book.
   - Recommend the next chapter based on the current chapter title.

2. **Steps Involved:**

   1. **Reading and Preprocessing:**
      - Read the text file containing the book.
      - Store the content in a variable for further processing.
   
   2. **Extracting Chapters and Their Titles:**
      - Use regular expressions to split the book into chapters based on a pattern.
      - Ensure the first element is a header and remove it if necessary.
      - Define a list of chapter titles.
      - Prefix chapter titles to their respective content.

   3. **Recommendation Logic:**
      - Define a function to recommend the next chapter based on the current chapter title.
      - Iterate through the list of chapters to find the current chapter.
      - Return the next chapter if available, otherwise indicate the end of the book.

   4. **Example Usage:**
      - Demonstrate the recommendation logic by providing an example chapter title.
      - Print the recommended next chapter.

   5. **Optional Step:**
      - Save the recommended next chapter to a text file.

3. **Output:**
   - Display the recommended next chapter.
   - Optionally, save the recommended chapter to a file.

This project demonstrates text processing using Python, including reading files, using regular expressions, and building a simple recommendation system based on text content.



**INPUT TXT FILE**

[final_corrected.txt](https://github.com/user-attachments/files/15960517/final_corrected.txt)

**OUTPUT TXT FILE**

[recommended_chapter.txt](https://github.com/user-attachments/files/15960522/recommended_chapter.txt)
