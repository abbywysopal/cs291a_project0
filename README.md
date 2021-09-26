# CS291a Project 0: Static Web Page

## Page Requirements
### Your static webpage must:
1. be hosted on GitHub Pages
2. be served via HTTPS
3. be created by hand – go nuts, but don’t use a page generator, i.e., no more markup than necessary
4. contain 100% valid HTML5
5. contain 100% valid CSS
6. utilize an external style sheet to provide style changes (no inline styles, i.e., provided via style attributes)

### You webpage must include:
1. a page title
2. a page heading
3. an image hosted on the same domain
4. an external CSS file written by you and hosted on the same domain
5. an unordered list with at least three items
6. a table with at least 2 columns and at least 3 rows
7. a hyperlink to the GitHub repository containing the source code

## Verification Script
The project0.py script in https://github.com/scalableinternetservices/ucsb_website/tree/main/scripts can be used to automatically verify that your webpage meets the necessary requirements.

Follow the directions in the README to clone the repository, install the python dependencies, and run the verification script.

## Questions To Answer
1. On average, how many requests can ab complete in 10 seconds with all the power of two concurrency levels between 1 and 256 (i.e., 1, 2, 4, 8, 16, 32, 64, 128, 256)?
  1 -> 81.7
  2 -> 686.3
  4 -> 1214.9
  8 -> 2300.8
  16 -> 4604.9
  32 -> 13612.2
  64 -> 27082.9
  128 -> 33305.7
  256 -> 36805.9
  
3. Why are there diminishing returns at higher concurrency levels?


5. What’s the performance difference when requesting HTTP and HTTPS?


7. How can github respond so quickly?


9. What is your site’s “Time to Interactive” according to PageSpeed Insights?
