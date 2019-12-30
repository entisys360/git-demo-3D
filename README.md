![Logo of the project](/docs/Monopoly_House.jpg)

# 3D Git Demo
> A simple Git demo using 3D CAD files to collaboratively build a house

A demonstration Git repo using STL files to collaboratively build a 3D model 
of a house using iterative change.


## Installing / Getting started

To get started simply clone this repository and import house.stl to the 
3D CAD software of your choice.

```shell
git clone https://github.com/entisys360/git-demo-3D.git
```

### Prerequisites

In order to modify the contents of this repository you will need software 
capable of reading and modifying STL files.

If you do not have 3D CAD software installed locally you can use resources
from the web to make modifications. 
I recommend https://www.tinkercad.com for editing in your browser.

### Deploying / Publishing

If importing the existing files results in a new or renamed file you must
export and copy the new files back into place overwriting the original
file that's been modified.

Add the modified files to your checkout create a valid commit message and
push those changes back to the Git server to publish.

```shell
git add modified_files
git commit -m "What changed and why"
git push -u origin your_branch
```

## Tests

Do your modifications still look like a house? Is your upgraded house better 
than the house that came before it?

