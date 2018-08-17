# dita-classic-pdf-landscape-sample
PDF customization folder which allows you to define landscape orientation for a certain chapter. Based on the samples provided by Mona Ross from Ellucian, samples based on examples in the DITA For Print book.
This is a customization folder so you need to set the DITA OT parameter "customization.dir" to point to the "Customization" folder contained in this project.

For example if your DITA Bookmap has a reference to a chapter:

            <chapter href="topics/installing.dita">....
            
and inside the "installing.dita" you have an 'outputclass='landscape'' attribute set on the root element, the output PDF will show this topic with landscape orientation
