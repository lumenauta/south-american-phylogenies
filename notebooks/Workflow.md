# Getting the initial data from HGN
1. scrape_hgn.ipynb
   > Pulls the data from HGN, as shown in basic_vocabulary_full.csv 

# Processing the HGN data
2. concepticon matching.ipynb
   > Matches HGN glosses to Concepticon concepts
3. clean_glosses.ipynb
4. map_glottocodes.ipynb
5. fix_basic_vocabulary_full.ipynb
6. cleaning_part_2.ipynb
7. splitting double_entries.ipynb
8. strip_parentheses_spaces.ipynb
9. non_ipa_characters.ipynb
    > Apply several processes to clean and enrich the HGN data.
10. match_glottocodes.ipynb
    > Matches language names to glottocodes in languages_with_glottocodes.csv to the main HGN vocabulary file.
11. match_glosses.ipynb
    > Matches glosses in glosas_unicas_hgn-mapped.tsv to the main HGN vocabulary file.

# Processing the protoform data
12. fix_proto.ipynb
    > Cleans the source protoforms files.
13. concepticon matching.ipynb
    > (Re-used) Maps the proto-forms to Concepticon concepts.
14. mapping_proto.ipynb
    > Adds the Gloss column to the main proto dataset.

# Incorporating the lexibank data
15. join_cldf_files.ipynb
    > Joins the 'forms', 'languages' and 'parameters' files of the lexibank sources.
16. merge_lexibanks.ipynb
    > Consolidates all joined lexibank datasets into a single file.
17. merge_hgn_lexibank.ipynb
    > Incorporates the lexibank datasets into our main file.
18. drop_duplicates.ipynb
    > Drops duplicate entries present in both the HGN dataset and the lexibank ones.

# Adding geographical metadata
19. mapping_coordinates_glottolog.ipynb
    > Adds coordinates based on Glottolog's 'languages_and_dialects_geo.csv'

# Generating the CLDF compliant files
20. cldf.ipynb
22. json.ipynb
