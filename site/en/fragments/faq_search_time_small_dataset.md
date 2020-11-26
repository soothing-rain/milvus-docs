If the size of the dataset is smaller than the value of <code>segment_row_limit</code> that you set when creating a collection, Milvus does not create an index for this dataset. Therefore, the time to query in a small dataset may be longer. You may as well call <code>create_index</code> to build the index.