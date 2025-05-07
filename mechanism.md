# How CORD works 

Different regions of an image respond differently to compression . CORD uses this phenomenon to it's advantage . CORD works by analyzing how different regions of an image respond to compression . Firstly , it divides an image into small blocks and each block is analyzed using one of three methods - DEFLATE compression ration , DCT frequency analysis or entropy calculation . CORD measures how "compressible" each block is while keeping in mind that similar visual content will have similar compression characteristics . 

After CORD obtains compression scores for all individual blocks , it applies K-means clustering to group blocks with similar compression properties into segments thus segmenting an image based on visual content .
