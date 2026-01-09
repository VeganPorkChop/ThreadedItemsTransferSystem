# Threaded Items Transfer System
# Planning
## Problem

| Problem | Solution |
| - | - |
| At the end of the school year, all of the nuts and bolts, etc. are not sorted and take hours to sort. | Our solution to this problem is a muti-stage machine that sorts everything into their respective sorted buckets. |

## Requirements 

| Essential | Non-Essential |
| - | - |
| The ability to sort between the “main groups” of materials in the lab. These materials are the tiny equipment: tiny nuts and bolts; the different nuts: lock nuts and normal; the different types of washers will be grouped because of the many micro differences; and sort the screws into their own catagory. | This will consist of sorting the tiny nuts from the tiny bolts, sorting the screws into M1, M2, M3, M4 etc., a higher accuracy in all of the components, and finally connecting all of the modules. This will be a module based project, so the user will have to manually move the unsorted pile from one system to another; therefore, the final non-essential requirement, and the point of why we put the word “auto in the title, will be to connect the modules and make it fully automatic. |

## Sucess Statement:
Success is measured through a 90% accuracy in sorting and zero total jams in the sorting of essential materials. Additionally, it will be essential that this project is documented to a level that could make anyone able to fix any problem that occurs.

# Conceptualize and Plan

### Materials we have to sort:
* #1-72, 3/8 Inch Bolts.
* #1-72 Nuts.
* #4-40 1/4 Inch Bolts.
* #4-40 3/8 Inch Bolts.
* #4-40 1/2 Inch Bolts.`
* #4-40 1 Inch Bolts
* #4-40 Nuts.
* #4-40 Lock Nuts.
* Washers

### Flow Chart

```mermaid
---
title: TITS Flow Chart
---
graph LR
A[Everything]
    A -->B{{ The _ Machine. }}
    B -->D[Tiny Items]
    D -->E{{ The _ Machine. }}
    E -->F[Tiny Bolts]
    E -->G[Tiny Nuts]
    B -->H[The Rest]
    H -->I{{ The _ Machine }}
    I -->J[Washers]
    I -->K[The Rest]
    K -->L{{ The _ Machine }}
    L -->M[Screws]
    M -->N{{ The _ Machine }}
    N -->O[#4-40 1/4 Inch Bolts]
    N -->P[#4-40 3/8 Inch Bolts]
    N -->Q[#4-40 1/2 Inch Bolts]
    N -->R[#4-40 1 Inch Bolts]
    L -->S[Nuts]
    S -->T{{ The _ Machine }}
    T -->U[Nuts]
    T -->V[Lock Nuts]
```

### Timeline

```mermaid

gantt
    tickInterval 1week
    weekday monday
    dateFormat  YYYY-MM-DD
    title       Timeline of Project

    section Modules That Graham Has To Do
    Cylinder Sorter : 2024-8-26, 3w
    Washer Track : 2024-9-16, 2w
    Bolt Sizer : 2024-9-30, 4w
    Documenting So Far : 2024-10-28, 2w
    Integration : 2024-11-11, 3w
    Finish Documentation : 2024-12-2, 1w

    section Modules That Jakob Has To Do
    Input Control System : 2024-8-26, 3w
    Initial Screenings #1 : 2024-9-16, 2w
    Bolt Sizer : 2024-9-30, 4w
    Initial Screenings #2 : 2024-10-28, 2w
    Integration : 2024-11-11, 3w
    Finish Documentation : 2024-12-2, 1w

    section School Breaks 
    Labor Day : 2024-09-02, 1d
    Professional Learning Day : 2024-09-22, 1d
    Teacher Workday : 2024-10-18, 1d
    Teacher Workday : 2024-11-4, 1d
    Teacher Workday : 2024-11-5, 1d
    Thanksgiving Break : 2024-11-27, 3d

    Project Due : milestone, 2024-12-08, 1d
    
```

# SYSTEMS DOCUMENTATION
## The New Plan
Forget that whole plan you just saw. This is the actual plan, we realized very quickly that the hexagons could do the whole thing.
```mermaid
---
title: TITS Flow Chart
---
graph LR
A[Everything] --> B[Everything] & C[Standoffs]
B --> D[Everything] & E[Lock Nuts]
D --> F[Everything] & G[Bolts]
F --> H[Everything] & I[Normal Nuts]
H --> J[Small Nuts and Bolts] & K[Washers]


```
## Hexagonal Sorter
![NutsFrumScroos](https://github.com/user-attachments/assets/577fb2f7-2d89-4c10-be38-7b475fd13abc)
<img width="5095" height="3296" alt="PVC pipe module" src="https://github.com/user-attachments/assets/76abc1a7-f9ce-4df1-ab94-a7332ed5ec53" />
Each wall has a section taken out of it, a cut from the floor of the hexagon to a specific height. That height is measured to match the size of a particular object that this hexagon is designed to catch. In other words, think of it like a net. If you want to catch big fish, you don't use a closely knit/stitched net, you use a net with lots of space between the string to let the smaller fish fall through. Our stackable design is like fishing for hardware. We increasingly shrink the size of the net, from catfish catching size, to minnow catching size. In this case, minnows are our washers.

## Final Pictures
![IMG_2047 (1)](https://github.com/user-attachments/assets/afdb7652-3bf0-4dcf-9d11-d9fe65689313)
![IMG_2049 (1)](https://github.com/user-attachments/assets/5601f3ec-32ba-4596-885a-106949b59158)
![IMG_2048 (1)](https://github.com/user-attachments/assets/96dcd6a7-66b5-4d96-aa7e-74c0b23d1816)
![IMG_2046 (2)](https://github.com/user-attachments/assets/a12b3dcb-eea2-4d73-80e8-bcfd5c5ebe67)
![IMG_2045 (2)](https://github.com/user-attachments/assets/2685659a-ddf4-41e9-b3b0-efc49692822d)


### HOW TO FIX ME?
There are only a few things that could go wrong with this design.
* The Acrylic Cracks
If this happens, just replace it. There are many redundant screws on the design, so even if one slot falls off or breaks it [should be ok.](#Docs)
* Its Connection Breaks
This is about the servo cap and servo connections with the hexagon. In this scenario, reprint the cap. We used the 4-way servo heads, and tiny bolts to secure the servo head to the servo cap.

# HOW TO FIX?
## Docs
[ONSHAPE:](https://cvilleschools.onshape.com/documents/672aa126c75f0bf0336b9dc3/w/92cd48f3c5af96a529a629e5/e/90918945a4e4bde3b3b8e3b7)
