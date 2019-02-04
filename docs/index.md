<a href="#hardware">Click here to learn about the Hardware</a>
------

<a href="#package layout">Click here to learn about the file layout in the package</a>
------

<a href="#startup">Click here to learn about the how to start up the Gummi Arm</a>
------

# Introduction
Gummi_head_twodof is the head package for the Gummi Arm. It is one of many packages used in the Luffy version of the Gummi Arm and it is a package that contains all the files pertaining to the use of the two degree of freedom head used on Luffy. Below are links to all the packages involved in running the Luffy version of the Gummi Arm.

The packages are as follows:
- gummi_base_luffy      [link to repo](https://github.com/nortonkellyboxall/gummi_base_luffy)
- gummi_ee_luffy        [link to repo](https://github.com/nortonkellyboxall/gummi_ee_luffy)
- gummi_head_twodof     [link to repo](https://github.com/nortonkellyboxall/gummi_head_twodof)
- gummi_interface       [link to repo](https://github.com/nortonkellyboxall/gummi_interface)
- gummi_moveit          [link to repo](https://github.com/nortonkellyboxall/gummi_moveit)
- gummi_hardware_Luffy  [link to repo](https://github.com/nortonkellyboxall/gummi_hardware_Luffy)

Each of these packages are connected and required to be cloned or forked.

<a id="hardware"> Hardware </a>
======
The head package encapsulates the head yaw and head pitch joints (as well as accompanying links). The joints are not VSA joints but can connect to the same bus as the other dynamixel motors. The links are all printed in nylon with the model able to be found in the gummi_hardware_luffy repo. 

<img src="images/Gummi_head.png" alt="Gummi Head"/>

<a id = "package layout"> Package layout </a>
======
The file system layout for this package is identical to the gummi_base_luffy package. Refer to that for further information. 

<a id = "startup"> Start Up </a>
======
This package is only referenced in startup. To see how to start up the arm refer to the gummi_base_luffy website.