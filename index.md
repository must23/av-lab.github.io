---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<style>
.banner{
    content: url("/assets/img/gen.png");
    float:right; width:40%; 
    margin-top: -2rem;
    margin: 10px;
}
@media (max-width: 600px) {
    .banner{
        float: none;
        display: block;
        margin-left: auto;
        margin-right: auto;
        content: url("/assets/img/banner-small.png");
        width: 100%
    }
}
</style>

# Autonomous Vehicle Lab 
<img class='banner'/> 
Welcome to the Autonomous Vehicle Lab (AV-Lab) at [Khalifa University!](https://ku.ac.ae) Our research focuses on Autonomous Vehicle (AV) technologies and the integration aspects into smart cities.

Safety assurance is a significant barrier to deploying AVs on a massive scale. Technical challenges arise from the uncertain environment, such as road and weather conditions, behavioral uncertainty of pedestrians and surrounding vehicles, and modeling inaccuracies. Our research direction is constructed around the following thoughts:

- How can we build safety within and around the core components of AV decision-making pipeline?
- How can each component reasonably report and parse uncertainty from dependent ones in an efficient and explainable manner?
- How can we build decision-making schemes that take the best out of the machine learning community and the rigor of theoretical computer science to achieve provably safer schemes without sacrificing efficiency?
- Exploit enabler technologies such as vehicle-to-everything (V2X) to build multi-agent solutions to realistic problems


[![](assets/img/sys-summer-2022.png)](tutorials)
