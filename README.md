# Third Eye: The Dark Pattern Detector for Online Shopping

Introducing Third Eye, a revolutionary Chrome extension specifically designed to identify and illuminate dark patterns on e-commerce websites. This innovative tool meticulously examines product pages, pinpointing and categorizing instances of dark pattern usage. Whenever a potential dark pattern is detected, it's not only highlighted but also accompanied by an informative popup, elucidating the type of dark pattern you're encountering.

<p align = "center">
    Example of an e-commerce page, with dark patterns marked in vivid yellow
</p>

<div align="center">
    <img src="https://drive.google.com/uc?export=view&id=1UOQi7rOx1WI0lw--DsNy1u62YwvQTAru" alt="Your Alt Text">
</div>


## What Exactly Are Dark Patterns?

Dark patterns represent a range of design strategies that subtly influence user behavior within software interfaces. While some are relatively benign, like using eye-catching colors for sign-up buttons, others veer towards being deceitfully manipulative. Particularly in the realm of online shopping, these patterns can subtly coerce customers into making unnecessary purchases. To deepen your understanding of dark patterns, visit this informative site. This resource, developed by the very person who introduced the term ‘dark patterns,’ offers invaluable insights into recognizing these covert design tactics.

## Behind the Scenes: The Technology Powering Third Eye

The front-end of Third Eye, the part that interacts with your browser, is crafted in Javascript. It scans the current webpage, gathering text for analysis. The heavy lifting happens in the back-end, where a Python-based server, utilizing Flask, processes this text. Here, Bernoulli Naive Bayes models meticulously classify the text snippets. The training of these models is grounded in research data supplemented by meticulously annotated datasets, ensuring a high level of accuracy in detecting dark patterns.


