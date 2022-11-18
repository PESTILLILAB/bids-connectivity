# BIDS Connectivity Project
### Developing a practical standard to report brain connectivity experiments.

The Brain Imaging Data Structure (BIDS) is community-driven standard meant to maximize neuroimaging data sharing, and facilitate analysis tool development. Over the past year the standard grew tremendously. BIDS was initially scoped to MRI data of the brain, but the standard has set up a solid infrastructure to steer the community and has been extended to cover a range of other modalities (PET, EEG, MEG, ECoG). Since its first announcement, BIDS has evolved to become an organized community with shared governance and a strong impact well beyond the U.S. BRAIN initiative. To date, 131 individuals among faculty, students, and postdocs contributed to the development of the standard and the article describing BIDS has been cited 277 times.

Besides the success, expansion, and description of multiple data modalities, gaps still exist in developing the standard to effectively support the process of scientific results reporting. This is because the standard does not yet describe advanced brain features that can be derived from all these data and that are routinely used to perform statistical analysis and complete scientific studies. These brain features comprise connectivity maps, structural and functional connections, major white matter tracts, diffusion signal models as well as white matter tractograms and tractometry. Sharing processed data and features in addition to raw and minimally-processed data is critical to accelerating scientific discovery. This is because substantial effort, software, and hardware instrumentation, and know-how are required to bring raw data to a usable state.

The aim of the present project is to extend the BIDS standard to encompass derivatives resulting from experiments related to macroscopic brain connectivity. The project is supported by the U.S. National Institutes of Health NIMH R01-MH126699.

## Run Locally

```bash
hugo server -D
```
