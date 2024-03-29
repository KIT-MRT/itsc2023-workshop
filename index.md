---
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: assets/images/header_from_unsplash_dot_com.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
title: 'Probabilistic Prediction and Comprehensible Motion Planning for Automated Vehicles – Approaches and Benchmarking'
excerpt: ''
---

Research on Automated Vehicles has experienced vast progress over the last decades. Today, first prototypes are sufficiently safe to drive on selected roads in public traffic. Nevertheless, safety comes at the price of overly conservative behavior, leading to inconvenient situations, for example, at unprotected left turns or merging scenarios. Presumably, the main reasons for this behavior include (a) errors in the prediction of other traffic participants, especially in interactive scenarios and (b) the lack of probabilistic considerations in motion planning. 


**Comfortable Automated Driving**: While safety should never be put at risk, worst case behavior of others should not be the default for the motion plan of an automated vehicle. Rather, with a safe reaction to such worst case behavior always in reserve the intended trajectory should be comfortable, less conservative and thereby potentially closer to human expectations. Proposal and exchange of these kind of approaches is the first aim of the workshop. 


**Multimodal Behavior Prediction**: For such behavior, sophisticated behavior prediction approaches for other traffic participants are necessary, going beyond constant velocity assumptions. Predictions must be probabilistic and allow for maneuver options for other vehicles. Often, there is not “the right prediction”, but many. The choice is influenced by destinations as much as individual driving behaviors and potentially even the drivers’ mood. Thus, a simple evaluation against a ground truth is not possible. Prediction approaches, including but not limited to machine learning based approaches, as well as proposals for their evaluation, are the second main goal of this workshop.


**Comprehensible Automated Driving**: For motion planning in highly interactive scenarios alike, a “ground truth” or “best option” may not exist. To be comprehensible and predictable for other road users, a good plan should be a subset of an expected prediction for a vehicle in the same situation. The combination of planning and prediction, including but not limited to their evaluation and benchmarking, is the third aim of this workshop.


**Effects of Automation on Traffic**: Data-driven predictions can end up being implicitly conditioned on second-order effects. For example, seeing a recording vehicle or no driver in an autonomous car can influence traffic participant’s decisions. Fixed settings in automated functions, such as safe distances, can influence the traffic flow on highways. While this can potentially introduce a distribution shift for prediction algorithms it could be also leveraged to purposefully shape traffic. We invite therefore also approaches investigating these second-order effects, propagating in highly interactive scenarios.


## Topics
The topics of interest of the workshop include, but are not limited to:

- Cooperative and comprehensible motion planning 
- Probabilistic decision making and motion planning (including MDPs, POMDPs, MMDPs) 
- Probabilistic behavior prediction (with help of semantic high-definition maps) 
- Second-order effects in heavy interactive scenarios
- Evaluation and benchmarking of the aforementioned topics


## Preliminary Agenda (Times and order may change)

| Time  | Name                | Affiliation                                                | Title                                                                                              |
|-------|---------------------|------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| 14:00 | **Welcome**         |                                                            |                                                                                                    |
| 14:15 | Kanghoon Lee        | Korea Advanced Institute of Science and Technology (KAIST) | Robust Driving Policy Learning with Guided Meta Reinforcement Learning                             |
| 14:35 | Tim Puphal          | Honda Research Institute Europe GmbH                       | Decisive and Comfortable Behavior Planning for Cooperative Driving                                 |
| 14:55 | Julian Schumann     | TU Delft                                                   | Using Models Based on Cognitive Theory to Predict Human Behavior in Traffic: A Case Study          |
| 15:15 | Chris van der Ploeg | Eindhoven University of Technology, TNO Automotive         | Occlusion-Aware Model-Predictive Planning Using Piecewise Continuous Risk Fields                   |
| 15:35 | Jonas Sjöberg       | Chalmers University of Technology                          |  Why we don't like interaction in traffic                                                                                               |
| 16:00 | Helen Gremmelmaier  | FZI Forschungszentrum Informatik, Karlsruhe                | Bicyclist behavior: An overview of the features and methods of trajectory modeling                 |
| 16:30 | **Coffee Break**    |                                                            |                                                                                                    |
| 16:50 | Philipp Geiger      | Bosch Center for Artificial Intelligence                   | On Learning the Tail Quantiles of Driving Behavior Distributions via Quantile Regression and Flows |
| 17:10 | Carlos Fernandez    | Karlsruher Institut für Technologie (KIT), Karlsruhe       | Behavior Prediction and Decision Making – The UNICARagil Case Study                                |
| 17:30 | Johannes Fischer    | Karlsruher Institut für Technologie (KIT), Karlsruhe       | Learning models for behavior planning in belief space                                              |
| 17:50 | Elisa Gaetan        | University of Modena, Italy                                | Exploiting Opinion Dynamics Models for Traffic Predictions                                                                                                   |
| 18:10 | All speakers        | Panel Discussion                                           |                                                                                                    |
| 18:40 |                     |                                                            | Closing Remarks                                                                                    |
| 19:00 |                     |                                                            |                                                                                                    |

## Organizers

<style>
td, th {
   border: none!important;
}
th:empty {
    display: none;
}
table {
  empty-cells: hide;
}
</style>


||||
| :-: | :-: | :-: |
| <img src="https://cloud.minesparis.psl.eu/index.php/s/8Ih7coZPaAkRkId/download" width="196" height="250"> | <img src="https://cloud.minesparis.psl.eu/index.php/s/uM0S69C2HvK1P0g/download" width="196" height="250"> | <img src="https://cloud.minesparis.psl.eu/index.php/s/xUp0YRt2gkYeCrW/download" width="196" height="250"> | 
| **Sascha Hornauer**<br /> MINES Paris | **Maximilian Naumann** <br /> Bosch Center for<br /> Artificial Intelligence (BCAI) | **Eike Rehder** <br />  Robert Bosch GmbH |
<img src="https://cloud.minesparis.psl.eu/index.php/s/EeNQ4Sd6Xvd3bpj/download"  width="196" height="250"> | <img src="https://cloud.minesparis.psl.eu/index.php/s/St0MsMoWj08Ui6K/download"  width="196" height="250"> | <img src="https://cloud.minesparis.psl.eu/index.php/s/nR8bFlVEe4QlsPp/download"  width="196" height="250"> |
| **Jiachen Li** <br /> Stanford University | **Wei Zhan** <br /> University of California<br /> at Berkeley | **Martin Lauer** <br />  Karlsruhe Institute of<br /> Technology (KIT) |
| <img src="https://cloud.minesparis.psl.eu/index.php/s/QATKLUjJ1l2BA6F/download"  width="196" height="250"> | <img src="https://cloud.minesparis.psl.eu/index.php/s/EHn5azQzYNmRmM0/download"  width="196" height="250"> | <img src="https://cloud.minesparis.psl.eu/index.php/s/F2fdqs7ZuidY5fW/download"  width="196" height="250"> |
| **Masayoshi Tomizuka** <br /> University of California<br /> at Berkeley | **Arnaud de La Fortelle** <br /> Heex Technologies | **Christoph Stiller** <br /> Karlsruhe Institute<br /> of Technology (KIT) | 


Please get in touch with  [sascha.hornauer@mines-paristech.fr](mailto:sascha.hornauer@mines-paristech.fr) or any of the organizers in case you have any further questions.


