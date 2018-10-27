# Adult Learning Campaign Page

The project and underlying files here are no longer actively maintained.

This repo was used to build the Adult Learning Campaign pages. These Campaign pages launched on October 25th 2018 on the Canada.ca website. It is expected that the Campaign pages will be removed from the Canada.ca website around July 2019. 

## Preview Links 

* [English Adult Learning Page](https://canada-ca-adult-campaign.netlify.com/en/)
* [English Student Grants Page](https://canada-ca-adult-campaign.netlify.com/en/student-grant/)

* [French Adult Learning Page](https://canada-ca-adult-campaign.netlify.com/fr/)
* [French Student Grants Page](https://canada-ca-adult-campaign.netlify.com/fr/bourse-etudiant/)

## Building / Customising the Project 

* Download the Project Files and drop them in a directory of your choosing
* Download and install the latest version of [Hugo](https://gohugo.io/)
* Find your directory and in a command line type:

  `hugo server --disableFastRender`

* Modify the files in your directory using your favourite text editor 
* Check out the results on the localhost server that [Hugo](https://gohugo.io/) runs

## Ingredients for the Project 

### CSS

As a general rule, Bootstrap and WET ultility classes were used as a first step, and then anything I couldn't do with those base styles I wrote custom CSS to fill in the gaps.  

If you are interested in the CSS you can find it here: 

* [CSS File](https://github.com/neilmispelaar/canada-ca-adult-campaign-page/blob/master/static/css/adult-campaign.css) 

### HTML 

Nothing overly special was done with the HTML. 

You can find the source for the pages here: 

* [English Adult Learning Source Code](https://github.com/neilmispelaar/canada-ca-adult-campaign-page/blob/master/content/en/_index.html)
* [English Student Grants Source Code](https://github.com/neilmispelaar/canada-ca-adult-campaign-page/blob/master/content/en/student-grant/_index.html)

* [French Adult Learning Source Code](https://github.com/neilmispelaar/canada-ca-adult-campaign-page/blob/master/content/fr/_index.html)
* [French Student Grants Source Code](https://github.com/neilmispelaar/canada-ca-adult-campaign-page/blob/master/content/fr/bourse-etudiant/_index.html)

### JavaScript

No custom JavaScript was used in the development of this project. 

### Tools 

* Build Engine: [Hugo.io](https://gohugo.io/)
* WET Template: [CDTS v4.0.28](https://ssl-templates.services.gc.ca/app/cls/wet/gcweb/v4_0_28/)
* CI and Hosting: [Netlify](https://www.netlify.com/)

## License

MIT
