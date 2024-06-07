# Schizosymphony
Schizosymphony is an artistic composition that intricately weaves urban soundscapes into a unified auditory experience. This piece sonifies a narrative soundscape by assigning distinct audio elements to 53 Intrinsic Connectivity Networks (ICNs), organized according to the primary categories mapped to 7 Functional Domains (FDs). This method creates a cohesive urban landscape, capturing moments from daily life typically encountered by a patient and merging them into a singular sound scene.

## Sound Link
[![Shizosymphony (2024)](https://img.youtube.com/vi/un1yZxA48wM/0.jpg)](https://www.youtube.com/watch?v=un1yZxA48wM)

## Data and Data Preprocessing
The functional magnetic resonance imaging (fMRI) data from the [Function Biomedical Informatics Research Network (FBIRN)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4651841/) dataset were processed with the [NeuroMark](https://www.sciencedirect.com/science/article/pii/S2213158220302126) pipeline. Subject-specific functional components and corresponding time courses were then estimated using the spatially constrained independent component analysis (ICA). The spatial components are the spatial maps of intrinsic connectivity networks (ICNs). These 53 ICNs can be grouped to 7 functional domains (FDs) according to their functional properties, including the subcortical (SC), auditory (AU), sensorimotor (SM), visual (VI), cognitive control (CC), default mode (DM) and cerebellar (CB) domains.

## References

[NeuroMark: An automated and adaptive ICA based pipeline to identify reproducible fMRI markers of brain disorders](https://www.sciencedirect.com/science/article/pii/S2213158220302126)

[The Function Biomedical Informatics Research Network Data Repository](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4651841/)
