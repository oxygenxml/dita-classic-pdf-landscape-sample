# dita-classic-pdf-landscape-sample
PDF plugin which allows you to define landscape orientation for a certain chapter. Based on the DITA For Print examples.

For example if your DITA Bookmap has a reference to a chapter:

            <chapter href="topics/installing.dita">....
            
and inside the "installing.dita" you have an 'outputclass='landscape'' attribute set on the root element, the output PDF will show this topic with landscape orientation.
