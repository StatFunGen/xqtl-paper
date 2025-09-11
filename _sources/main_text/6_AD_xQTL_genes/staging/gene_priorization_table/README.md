## Slack message from Alexandre Pelletier on Friday Aug 15, 2025

Hi @gaow and @Ru Feng, The scripts to generate the table is in  s3://statfungen/ftp_fgc_xqtl/interactive_analysis/adpelle1/xqtl-paper/analyses_summary/complete_ADlocus_level_summary.R

if you want to regenerate only for polishing /change column name, you just need to run part IV)

column names and format are described in a metadata that I have in s3://statfungen/ftp_fgc_xqtl/interactive_analysis/adpelle1/xqtl-paper/analyses_summary/columns_metadata.tsv

this table can be modified the way you want to change the displayed column names, the width, scale coloring etc

there is second level metadata associated to this one that deal with the wildcard I ve put for the broad contexts repeating columns s3://statfungen/ftp_fgc_xqtl/interactive_analysis/adpelle1/xqtl-paper/analyses_summary/columns_metametadata.tsv where you can change also some formating (edited) 
