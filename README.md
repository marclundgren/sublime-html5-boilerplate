# Sublime HTML5 Boilerplate

A Sublime Text 2/3 snippet to generate the HTML5 Boilerplate (v4.3.0) template.

## Install

Copy the files to your Packages directory.

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'HTML Boilerplate' then press enter to install.

## Usage

With a blank HTML file open, type

    htmlboiler

and press `TAB`.

That generates:

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <title>${1}</title>
            <meta name="description" content="${2}">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            <link href="http://cdn.alloyui.com/2.0.0/aui-css/css/bootstrap.min.css" rel="stylesheet"></link>
            <link href="http://cdn.alloyui.com/2.0.0/aui-css/css/bootstrap-responsive.min.css" rel="stylesheet"></link>

            <!-- Place favicon.ico and apple-touch-icon.png in the root directory -->
        </head>
        <body>
            <!--[if lt IE 7]>
                <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
            <![endif]-->

            <!-- Add your site or application content here -->
            <div class="row-fluid">
                <h1>Hello world! This is HTML5 Boilerplate with AlloyUI.</h1>
            </div>

            <script src="//cdn.alloyui.com/2.0.0/aui/aui-min.js"></script>

            <script>
                YUI().use('aui-base', function(A) {

                    // Place your AlloyUI code here
                });
            </script>
        </body>
    </html>

## License

[MIT Licensed](http://sloria.mit-license.org/).