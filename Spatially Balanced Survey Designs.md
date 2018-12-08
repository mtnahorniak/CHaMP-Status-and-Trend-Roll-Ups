## Spatially Balanced Survey Designs



Spatially balanced sampling designs aim to spread sampling points uniformly across the spatial domain of interest.  

The Generalized Random Tessellation Stratified (GRTS) sample selection algorithm was developed by Stevens and Olsen (2004) and has been used for regional monitoring programs, including several water quality programs funded by the EPA, Bonneville Power Administration, and Washington Department of Ecology, to name a few.

In 2012 the Integrated Status and Effectiveness Monitoring Program provided a free workshop on GRTS-based sampling designs and analysis, which was led by Don Stevens, one of the developers of the GRTS algorithm. 



## GRTS Workshop Training Materials (August 22-23  2012, Portland, OR)

 **Instructor: Dr. Don Stevens**

 

*Red Lion Hotel-Portland Convention Center*

*1021 NE Grande Ave.*

*Portland, OR 97232*



### DAY 1:  Introduction to GRTS and Study Design Development  (8:30 am-5pm)



#### Section 1.  Overview of GRTS (8:30-10am)

*History and origin of GRTS and overview*

 

Stratified and variable probability sampling

Inclusion probabilities

Site evaluation

Weight adjustments

 

#### Section 2.  Designing a GRTS sample for stream/river networks (10-12am)

*Introduction to stream network sampling as continuous, discrete or area based samples and the implications of how a response design is set up in these various scenarios* 

Limitations to application of GRTS along linear networks 

Specifying objectives: What do you want to estimate?  How does design tie to objectives?

Function of the response design and relationship to spatial/temporal design

Spatial design: target population, frames, stratification

Temporal patterns—panel designs

Sampling details: legacy incorporation, densifying the master sample, power analyses

Extract sample from a master sample

Generating initial weights, probabilities and densities

Documenting the design and generating a design file: what should it contain?

 

#### Lunch (on your own, 12-1pm)



#### Section 3:  Analysis (design based inferences)  (1-5pm)

 *Now that I’ve got my files together, site evaluations, and site metrics, how do I make inferences based on my design, and what do I get (theoretical meaning of results)?*

 

Distinguish design based inference from model based inference

Develop adjusted weights (how is this done, what is considered)

Categorical vs continuous estimates

Estimates and indicators: totals (e.g, how many fish do I have?), densities, frequency distributions

Sampling uncertainty and precision of estimates

Analyzing data using post-hoc stratification (how does this work?)

 -------------------------------------------------------------------------------------------------------

### DAY 2:  GRTS functions in R (8:30am-12pm)

 

#### Section 5:  Description and demonstration of functions available in spsurvey library or recent scripts developed by D. Stevens (e.g. CHaMP scripts)  (8:30-12pm)

*GRTS function for linear resources:*

Adjwgt function

Cont.analysis function

Cat.analysis function

Don’s specific functions (non-spsurvey version of GRTS code)

Use of GRTS for temporal patterns 

 

*Other:*

Generating a Master Sample (spsurvey)

 

Development of web based tool for extraction of samples from master samples: what will it contain and what is its status?

 