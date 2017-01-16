# OpenStreetMap and Smart GIS

## OpenStreetMap, Community and Evangelism

I've been an [OpenStreetMap][osm] [member][osmprofile] since 2007, and
was responsible for a lot of the original mapping and social events in
Brisbane, Australia.

While things have gotten a bit quiet for me and OpenStreetMap recently
(I got a bit bored when there were few big details left to survey), I
have organised around 20 [Brisbane Mapping Events][events] over the
past decade. I have also evangelized OpenStreetMap to universities and
local community groups on many occasions, such as this most recent
presentation for the [Royal Geographic Society of Queensland][rgsq] in
March 2016:

<iframe src="https://docs.google.com/presentation/d/1pZRXZ0eYwk_KaiHcfIFiGIXbK2-CYeVpIRna1dphOwM/embed?start=false&loop=false&delayms=3000" frameborder="0" width="480" height="389" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## Smart GIS - Road Detection from Aerial Imagery

These days, I'm trying to get back into mapping more, but I'm also
starting a focus on side projects for AI and machine-learning for GIS
applications to help the OpenStreetMap community.

I have already done some work in this space back in 2011, where I
worked with [Xufeng Guo][felix] to develop a dataset based on high-resolution
aerial imagery from NearMap (which was CC-licensed at the time) and
OpenStreetMap ground truth. We published our findings at the 2011
Digital Image Computing Techniques and Applications (DICTA) conference:

> X. Guo, **D. Dean**, S. Denman, C. Fookes and S. Sridharan,
> "[Evaluating Automatic Road Detection across a Large Aerial Imagery
> Collection][roaddetectpaper]," *2011 International Conference on Digital Image Computing:
> Techniques and Applications*, Noosa, QLD, 2011, pp. 140-145.

The paper can be downloaded above, and the slides from our
presentation can be viewed below:

<iframe src="https://drive.google.com/file/d/0Bw0XkNIYFiNbTkdZSV9MNEtLaWc/preview" width="480" height="389"></iframe>

Unfortunately, due to lack of interest, the university has not yet
made the database available, **but** I am currently working to rectify
this situation so that I may use it in my upcoming side projects.

## Smart GIS - Hacking on DeepOSM

I plan to fork the existing [DeepOSM][deeposm] project, and train and
evaluate it over our large collection of aerial imagery. From there,
more exciting things should follow, so stay tuned!

[roaddetectpaper]: http://eprints.qut.edu.au/47715/1/DICTA2011.pdf
[events]: http://wiki.openstreetmap.org/wiki/Brisbane/Events
[rgsq]: http://www.rgsq.org.au/
[osm]: https://openstreetmap.org
[osmprofile]: https://www.openstreetmap.org/user/David%20Dean
[deeposm]: https://github.com/trailbehind/DeepOSM
[felix]: https://au.linkedin.com/in/felix-guo-9a684157
