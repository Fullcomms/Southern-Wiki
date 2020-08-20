# View Listings Area

This area can be found within the CMS under Listings>View Listings or here at [View Listings](http://southern.test/admin/listing)

## Searching for a property

At the top of the page is the search functionality featuring 2 checkboxes to search based on the type of property, New Homes or Resales. Following this is the property name search which can take multiple inputs and is suggestive based on what you have typed and the properties that exist. Below the property name search is the property status search which as above also takes multiple inputs and is suggestive based on what has been typed in and whether that matches a status that exists. 

The most efficient way of searching for a single property is by using only the name search bar. This feeds into the reasoning behind giving properties uniquely identifiable names. For example having more that 1 Artisan listing would be problematic as you would have to select all properties named Artisan and check each listing for the one you are specifically looking to edit or manage.

The reset filter button will clear all existing search criteria.

## Pending Properties

In this new CMS there is no need to create listings from scratch due to the link between Full Circle & the Southern site.

Once a property has been created within Full Circle and all the necessary criteria and processes have been completed it will appear in the CMS under pending properties.

All financial information about the property is entered within Full circle along with the creation of plots. This is to remove any inconsistencies in property information between Full Circle & the CMS.

Once a listing has been created within Full Circle and has appeared in the pending properties area it's time to add any marketing information, images, descriptions, carry out customer journey management & add address information.

## Editing a Property

To edit a property simply click Actions>Edit & all the relevant fields will be displayed on the following page.

### Basic Listing Info

Basic listing info consists of the top level information about the listing such as the name both private (only seen by CMS users & Full Circle users) and public (seen on the frontend of the site). The status of the property (this may display a different name to the one in full circle, the status displayed here is the one that customers will see on the frontend of the site). The final part of this section is the slug, the slug is what is at the end of the url when viewing the listing on the frontend. This always has to be unique for obvious reasons & should never contain offensive or inappropriate content.

### Address

This section is pretty self explanatory, this is where you enter the address of the property and also set the latitude and longitude of the property which is calculated based on the postcode inputted which will access the google api and return the correct latitude and longitude.

The latitude and longitude is the most important part of this section as without it the default area is set to the centre of London.

### Images

This section has the most changes as the old image uploader & previewer is completely different in both functionality & ability.

The first part of this section is the image uploader with a short description on how to use. That button is useful only for uploading, managing, editing & cropping images to be used for the property.

The suggested way to use this is by creating a specific folder for the listing and uploading all images to that folder. This is to introduce a better folder structure to the images folder which eventually will speed up the image uploader as it loads on a folder by folder basis. if a folder contains 1000+ images obviously it will take longer for the uploader to open that folder however if a folder contains 1000+ folders of different properties it will load instantaneously due to no data being loaded.

The Gallery field is the trickiest to use and is possibly going to be tweaked in the near future to make using it more intuitive & efficient. If you're editing a property that is live & already has gallery images in order to add a new image to the gallery you will need to open the image uploader by clicking the folder icon on the input field & reselect all the currently used images along with any new images you want to add to the gallery. This feeds into the idea that having all images relating to a single listing being kept within a folder of it's own to make this process easier.

### Property Details

This area contains the descriptions of the property for example the small description which is placed above the image gallery on the frontend.

When pasting content into these from an external source it's important to highlight all the text inputted into the textarea and click the clear formatting button on the toolbar which looks like an underlined Tx.

This ensures that no font styles sneak through onto the frontend.

The restaurants and travel points take integer values of how many of the respective are close to the listing.

### Local Area

This area is only 2 inputs, one for the area name and another for the description, this will also need formatting clearing from it just to make sure. 

### Customer Journey & Notifications

The email notifications is a select dropdown, similar to the property name search, that takes multiple inputs. All people selected in this area will be assigned to receive emails regarding the property. For example if alex@fullcomms.co.uk is in that field then i would receive notification emails that Joe Bloggs has booked a viewing at 12:99PM on 12th Julember 2029.

Assessment mandatory being set to yes forces prospective customers to complete the pre-assessment process before being able to book a viewing on the property. This works in tandem with assigning a mortgage broker to the property. 

Sales Consultant, a lot like the email notifications input, is the owner of the listing from a sales point of view. The Sales Consultant selected on this input will also receive email notifications and is also in charge of managing the listing and enquiries related to the listing within Full Circle

Hit save and that will commit all the changes to the database.

NOTICE!! Hitting save will not set the property live, this gives you the chance to preview the listing and make sure everything displays as you require.