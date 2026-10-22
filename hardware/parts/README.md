# Drone Parts

The parts of the S.A.M airframe that we print ourselves. Every part has its
print file and a photo of how the print came out, so anyone can see what
we used and what it should look like.

## How this folder is organised

```text
hardware/parts/
├── files/     the print files (.stl, .3mf, .step), one per part
├── photos/    a photo of each finished print (.jpg or .png)
└── README.md  this page: the table of parts
```

Name a part's file and photo the same way, for example
`files/arm_front_left.stl` and `photos/arm_front_left.jpg`.

## Parts

| Part | Print file | The print | Material | Notes |
|---|---|---|---|---|
| *No parts added yet* | | | | |

To add a part, put its file in `files/` and its photo in `photos/`, then
add a row like this one:

```markdown
| Front-left arm | [arm_front_left.stl](files/arm_front_left.stl) | <img src="photos/arm_front_left.jpg" width="160"> | PETG | 20 % infill, printed flat |
```
