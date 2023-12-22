# ML_CyberSec_Attack_Classification


The proliferation of IoT networks and their rich repositories of user data have made them a prime focus for cyberattacks. Consequently, intrusion detection systems have been implemented to monitor and flag unusual network behavior. The UNSW-NB15 dataset, which encompasses a variety of network traffic scenarios, including both benign and malicious conduct, is instrumental in IoT-based network analysis. Utilizing the botnet data from this dataset, which includes information from IoT sensors, preliminary findings indicate the effectiveness of certain features in distinguishing between legitimate and malevolent activities. Machine learning algorithms play a crucial role in crafting a network forensic mechanism that leverages network flow indicators and characteristics to pinpoint and track botnet activity. Using the UNSW-NB15 dataset, machine learning methods have proven their ability to accurately identify and trace botnet incursions.

The initiative was further advanced by developing a classification model for the UNSW-NB15 data samples, employing a random forest and a feed-forward neural network. The random forest component of the system classifies the data as either normal or malicious. This classified data is subsequently utilized to train a neural network, which refines the classification into specific attack types. The model achieved notable success in detecting attacks, with a precision of roughly 0.88, and exhibited near-perfect precision in identifying normal data. While the model could generally categorize attacks into two distinct classes, it struggled with finer distinctions between types of attacks. Despite this, it was highly accurate in classifying normal network traffic. The development process encountered typical machine learning issues such as managing large volumes of data, memory constraints, and class imbalances, with the latter particularly impeding the ability to generalize across data classes.


