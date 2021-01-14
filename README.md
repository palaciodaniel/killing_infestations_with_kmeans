# Killing Infestations with KMeans

**NOTE:** In the -unlikely- event you have trouble visualizing the Notebook, you can enter the following [NBViewer link](https://nbviewer.jupyter.org/github/palaciodaniel/killing_infestations_with_kmeans/blob/main/killing_infestations_with_kmeans.ipynb).

For this project, although I did not experience any difficulty in writing the code at all, I spent several weeks thinking on an interesting subject idea for it. 

Using an aerial image was something I considered from the very beginning though, and my original plan revolved around a business (most likely a pizza store) whose owners wanted to open branches on other parts of the city, and in order to determine where exactly those new establishments should be, the dataset was going to consist on phone calls from customers whose location was triangulated.

However, although the idea was pretty satisfactory, and reflected a coherent business challenge, I felt it was too generic and kept thinking on other ideas.

After browsing for some time different aerial images on *Unsplash*, I found by pure chance the trainyard one and I knew immediately that it was going to be the selected one. Now I only needed to build a context around it.

<p align="center"><img src="https://images.unsplash.com/photo-1527498348926-888801f0a493?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"></p>

The first thing that came to my mind was about an intelligence agency whose analysts became aware of an incoming terrorist attack on that trailyard, so the dataset coordinates were going to represent individuals traveling on the different trains. Obviously, the more people concentrated at a particular train/carriage, the more likely someone was going to leave a suitcase with explosives there.

I liked that idea a lot, however the temporal dimension was going to make the Notebook unnecessarily long: the number of passengers obviously would not be the same during the early morning than during peak hours. Therefore I needed to think about something for which the time of the day was unimportant.

And that condition was the one that defined the general idea that you see implemented on the final version. After all, if the trainyard was abandoned for several years, then the infestation would be rampant despite the time of the day, so it would simplify the situation in a way that the main focus is still how an unsupervised Machine Learning algorithm could be applied to fix the problem.

Although this context is far from being completely realistic, and specially when compared with the pizza store idea, I still consider it more original and interesting to build a Notebook around.

## Credits

Code written by **Daniel Palacio**.

Abandoned train carriage image by **Bart Christiaanse** - *Unsplash.com* (https://unsplash.com/photos/LAYabUzmjbE)

Trainyard image by **Campbell** - *Unsplash.com* (https://unsplash.com/photos/rbBEs6Hljyg)
