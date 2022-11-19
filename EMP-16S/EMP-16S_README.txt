Here we provie a subset of Earth Microbiome Project results.

Following the scheme:
ftp://ftp.microbio.me/emp/release1/about_otu_tables.pdf
in
'emp_or_gg_13_8.release1_CAMDA_2019_sel.biom'
we are providing subset of 'emp_or_gg_13_8.release1.biom' (open-reference Greengenes) [ftp://ftp.microbio.me/emp/release1/otu_tables/open_ref_greengenes/emp_or_gg_13_8.release1.biom]

The file contains OTUs for 3,043 soil samples which have passed the QC filters.
Soil samples selection has been done with use of metatable
[ftp://ftp.microbio.me/emp/release1/mapping_files/emp_qiime_mapping_qc_filtered.tsv] with following filters applied:
- 'env_material' is 'soil' or 'bulk soil'
- 'envo_biome_1' is 'terrestial biome'
- 'sample_scientific_name' is 'soil metagenome'
the subset of original metatable is provided as 'CAMDA_2019_EMP_metainformation.tsv'

You can find more information about BIOM format and how to manipulate it here:
http://biom-format.org
