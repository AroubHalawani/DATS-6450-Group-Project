# DATS-6450-Group-Project


By: Pauline Mnev, Rachel Culbreath, Aroub Halawani

This project aims to develop a start to finish process for a business owner to automate the creation of customized cartographic postcards & posters.
By creating a script in Google Collaboratory, it enabled the team to utilize Google Forms in this process. This streamlined approach enables a business owner to share the link with a customer, who is able to input all of their customizations, and then the owner can simply run the script. This will output a ready made product for sale/sharing. The necessary "business owner" side of the project & assets is located in the shared Google Drive.

Instructions can be found in the [Insturctions Document](https://docs.google.com/document/d/19HInFwAmldsk6nT97ErP9CZ0Kl01iWB_CoAjs17NGQs/edit?usp=sharing) as well as the Google Collab
[Mapping.ipynb](https://colab.research.google.com/drive/18K-ciwIsS3paBEjGtoA4badTyYXPpDzz?usp=sharing)

This project runs completely on Google Collaboratory. The prettymaps project has been noted to have bugs when running off of desktop, and the team opted into using the Google Collab space as the creator of the package recommends it. 

This enabled collaboration through Google accounts rather than GitHub, thus, you will not see our activity / pushing into the space. 

There were several limitations of the prettymaps package, which we will discuss below:

* Limited documentation of a user created package. Since it is up to the creator to address/debug issues or answer questions, there is a limited number of resources available to the public. Therefore, there were several issues that we could not determine solutions for, but found workarounds. We had referenced community examples from Reddit & any videos we could find of documentation/walkthroghs of the package on YouTube.

1. Editing the watermark using matplot (this just was not a capability that we could access with the prettymaps package settings) 

2. Creating presets caused a lot of errors unless the presets were plotted into the script first. Therefore, we were unable to utilize prettymaps.create_preset(), and instead used prettymaps.save_preset(). To make sure the output of running the preset the first time didn't crowd the space, we silenced the output of those code blocks 

3. Ubuntu-font not found warning persisting within Google Collab space, even if font is imported & even if the font isn't even used. It is a warning, not an error, so it did not impede our work. 

4. Editing limitations due to using matplot versus prettymaps method. There were errors that other members of the community mentioned running into (via Reddit), but referenced that matplot works around these issues. However, it would be easier to customize if the proper method worked instead.

Next steps for the project:

Moving forward, it would be necessary to determine how to edit watermark to be less obstructive in the map. Additionally, it would be interesting to allow for higher levels of customization, such as positioning of text & labels within the map frame. Customizing textures within each layer would also be an interesting next step to pursue. Creating more presets for different themes such as University colors, holiday colors, State flag colors would also be an interesting next step. Additionally, widening the font selection would make the process more fun to customize. Finally, it would be beneficial to understand how to tweak the process to ensure that two users can't override each other's inputs in the Google Form. Perhaps having the script trigger to run automatically anytime a new form entry is input could be the solution to this. This would then require the script to save each map with a unique name.



