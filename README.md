# Darwin Text Analysis - Insectivorous Plants

This project performs an exploratory text analysis on Charles Darwin’s book *Insectivorous Plants* using Python. The goal is to understand how often key terms appear throughout the book and visualize their cumulative occurrence by chapter.

## 🔍 Project Overview

We retrieved the full text of the book from [Project Gutenberg](https://www.gutenberg.org/ebooks/5765), processed the text into individual chapters, and analyzed term frequencies across those chapters. We focused on five biological terms of interest: `insect`, `leaf`, `flower`, `plant`, and `rabbit`.

## 🧠 Methods Used

- **Web scraping**: Used `urllib` to fetch the raw text from Project Gutenberg.
- **Text processing**: Split the book into chapters using string manipulation.
- **Term frequency analysis**: Counted how often each of the five target terms appeared in each chapter.
- **Data analysis**: Used `pandas` to structure and manage term frequency data.
- **Data visualization**: Created cumulative line plots to visualize how term usage builds up over the course of the book.

## 📊 Outputs

- A table of term counts by chapter (`counts_df`)
- A cumulative line plot of term frequencies over 16 chapters

## 📁 Repository Structure

