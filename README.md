LatentDirichletAllocation
=========================

Implementation of Latent Dirichlet Allocation in C# (CSharp)

Executable can be found under Viewer/bin/x64/Release/
* Running Viewer.exe will launch the User Interface

After collecting the topics, you may use topic_extractor.py to extract the topics in json format
  
  	> util/topic_extractor.py input_directory_of_topics_collected/ output_topics_to_dir/

Conjunction with RenA
------
Suppose you used https://github.com/souleiman/RenA to collect attributes and NE and want to merge the attributes and NE.

	> util/merge_all.py [path_to_alda_json_files] \
			    [path_to_all_ner_attribute_json_files] \
			    [merged_output_directory] ([classifier_directory] [classifier_identifier])
	
