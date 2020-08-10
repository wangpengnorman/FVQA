# FVQA: Fact-based Visual Question Answering
It can be downloaded from [hear](https://www.dropbox.com/s/iyz6l7jhbt6jb7q/new_dataset_release.zip?dl=0).

./Images: the image files used by this dataset, which are extracted from COCO and ImageNet datasets.

all_fact_triples_release.json: the facts (triplets <e1, rel, e2>) corresponding to the visual concepts shown in the paper (object/scene/action), which are extracted from three knowledge bases, i.e., DBpedia, ConceptNet and Webchild.
-- r: the unique id of entity rel (relationship)
-- e1: the unique id of entity e1
-- e2: the unique id of entity e2
-- KB: the source of knowledge base
-- e1_label: the textual string describing entity e1
-- e2_label: the textual string describing entity e2
-- surface: the textual description of the fact

all_qs_dict_release.json: the collected questions and their associated supporting facts
-- fact_surface: the textual description of the supporting fact
-- ans_source: the source of the answer (Image or KB)
-- question: the collected question
-- answer: the answer to the question
-- img_file: the image filename corresponding to the question
-- visual concept: the visual concept corresponding to the supporting fact
-- fact: the unique id of the supporting fact
-- question id: the unique id of the question
