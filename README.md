This model is a new version based on GRACE and KGCL. It will contain different parts, consist of:
* KG
* CL
* LightGCN & GCN
* RS

Dataset is from Amazon datasets available in https://jmcauley.ucsd.edu/data/amazon_v2/index.html .

It's different parts will be add in next updates. Current predictable steps are:

* Read Data
* Embed texts(Descriptions) and initialize item nodes with them.
* Create KG from attributes such as genre and publisher
* CL for images
* CL for different created views
* RS part

Extra part(multi domain mode):
* Find best second domain
* Create the new graph and use LightGCN for initializing and then we have a new view
* combine view with first initialized embedding which was based on descriptions.
