# CTAO-image-processing-with-ants-algorithm

Image atmosferic Cherenkov telescopes (IACTs) are one of the main telescopes used to observe high energy gamma rays, which are crucial for the study of countless fenomena in the universe. The Cherenkov Telescope Array Observatory (CTAO) plans to build 64 of this IACTs in the comming years, the location for the observatories will be the Atacama desert in Chile and the Roque de los Muchachos observatory in the Canary islands, Spain. This way the the observatory will cover both hemispheres. The instrumental sensibility required to detect Cherenkov radiation lead to the recording of an amount of data each time more dificult to classify and process. With the aim of reducing cost of saving the data, an alternative representation with graphs is proposed. After creatting the graphs the ants algorithm is runn over them in order to find their optimal representation. Such representation proved to be a 50% in average more efficient in terms of memory consumption than other formats. Besides, since the data needs to be classified before studying it, three machine learning (Ml) algorithms were proposed to classify it. The performance of this models barely changed between the raw data and its graph representation. However, to our knowledge, this is the first work which attemps to represent CTAO data as graphs and classify them in that representation. Thus, the work presented here opens the path for future research on both the representation of the graphs and their classification.

The code used to obtain this results is showed here. Three self-explained notebooks were created, one to analyize and process the data, another one to create the graphs and a third one to classify each representation of the data.

Author: Germán Cano Amaro

Thesis-Director: Alberto Guillén Perales

Thesis-Co-director: Rubén López Coto

