# hmvc_codeigniter_template
This codeigniter combines modular programming with template / themes

NOTE: 
This codeigniter is an improvement on the one built by and found here: https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc

Changes
The template file was updated to work with templates.

Difference
Previously, a template was called with: 
$this->template->load('template_name', 'body_view');

Now it is called as 
$this->template->load('module_name','template_name', 'body_view');
where module_name = the name of the current module.

Installation
Follow these simple steps
 1. Follow the tutorial here: https://code.tutsplus.com/tutorials/an-introduction-to-views-templating-in-codeigniter--net-25648
 2. Use the 'Template.php' provided here.
 You are good to go.
