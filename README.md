# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is for students who are new to Berkeley and want to find useful campus services and places. The first eight resources were supplied by COMPSS 211A. I added the Recreational Sports Facility (RSF) and checked its details on the RecWell RSF Website(https://recwell.berkeley.edu/facilities/rsf/).

## Website checks

Live website: https://bellalu1109-beep.github.io/hidden-berkeley/. I improved the access note for Morrison Library (HB03) using the library's Morrison Website(https://www.lib.berkeley.edu/visit/morrison) and added the Recreational Sports Facility (HB09). In a private browser window, I checked that the page shows nine entries and that the Morrison and RSF entries show the same values as the CSV. Both official links opened the intended pages, and the CSV on GitHub includes the HB09 row.
