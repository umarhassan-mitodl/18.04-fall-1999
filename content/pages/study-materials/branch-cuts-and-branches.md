---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
parent_title: Study Materials
parent_type: CourseSection
parent_uid: 6bfe28ba-cff1-c966-5e04-5bab872d6fad
title: Branch Cuts and Branches
uid: 2f8fa18d-fac0-85df-46c6-ac5303441bc6
video_metadata:
  youtube_id: null
---

(All images created with MATLAB® software)

Click on pictures for more information and an image of higher resolution.

One way to get a single valued function out of a multiple valued function is to introduce **branch cuts** in the complex plane. These are curves joining the branch points in such a way as to prevent multiple values from arising (by eliminating paths that can go around the branch points). Then a single value can be selected (at each point in the cut plane) for the function. This then defines a **branch of the multiple valued function**.

We point out that the process by which a branch of a multiple valued function is constructed is somewhat arbitrary; the selection of the branch cuts is only limited by the fact that they must be there to prevent the multiple values from arising. This leaves a large amount of freedom in their selection. Thus, the branches of a multiple valued function are highly non-unique and (generally) there is nothing to make one branch special over another (excepting special reasons that may arise in specific applications and uses of complex variables).

{{< resource uuid="5c7cca7d-e77f-770a-2575-801445f44045" href_uuid="da92f666-217c-d89a-bca9-8306ff997b7c" >}}  
Figure 1: Real part of the Principal Value of the cube root.

Unfortunately, a price must be paid for the single valued function a branch of a multiple valued function provides. The price is that **branches are discontinuous along the branch cuts**. On the other hand, branches are necessary, since they provide the only practical way of actually doing computations that involve multiple valued complex functions.

We illustrate these points with the **example of the principal value of the cubic root on the complex plane**. This principal value is _defined_ by the following facts: **the branch cut is the negative real axis** and the branch takes **positive real values on the positive real axis**. Equivalently, **the argument of the cubic root is restricted to the range**: _\-π/3 \< θ \< π/3_. Figure 1 shows the real part of the principal value of the cubic root and Figure 2 shows the imaginary part. The discontinuity along the negative real axis (the branch cut) is quite evident.

Notice that, since this function can take only three values, on the complex plane cut as described here (along the negative real axis) only three possible branches can be defined. One is the principal value and the other two are just the principal value multiplied by one of the cubic roots of unity distinct from one; that is, multiplied by either: _e{{< sup "i2π/3" >}} or e{{< sup "\-i2π/3" >}}_

Furthermore, if we attempt to continue the function across the cut in a smooth fashion, the function (instead of taking the values given by the principal value) takes the values given by one of the other branches. This is a quite general phenomena: **Any given branch of multiple valued function connects smoothly with some other branch when a path crossing a branch cut is followed**. Here, as we cross the negative real axis, we will connect with one or the other of the two other branches, depending on which direction the crossing is made. In examples with many branch cuts and many possible branches, the situation can become quite confusing (the famous Minotaur labyrinth of Greek mythology might look trivial by comparison with the situations that relatively simple complex functions give rise to).

{{< resource uuid="f2392800-de97-7957-0571-0d6e006b6221" href_uuid="03be228f-7502-0e43-8699-16a0b6de4aed" >}}  
Figure 2: Imaginary part of the Principal Value of the cube root.