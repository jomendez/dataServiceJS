dataServiceJS
=============

This code is a wrap layer useful for capture and display errors early when you work with web apis, and something fails in the AJAX call, and also to extend the auth time
every time an AJAX call is made, you can use it as boilerplate to build your own. This class used the revealed pattern.
The libraries needed for this class to work correctly are JQuery and Bootstrap.


```JavaScript
//example of modal popup that works with the js class included (you have to include a reference to bootstrap library)
  <script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
    <link href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css" rel="stylesheet" />
    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css" />
    <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
```


```HTML
    <!--This is a Modal popup of Bootstrap 3.2 -->
    <div id="errorModal" class="modal fade">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <button type="button" class="close" data-dismiss="modal"><span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
                        <h4 class="modal-title">Error</h4>
                    </div>
                    <div class="modal-body">
                        <p> Oooops... Something went wrong</p>
                        <small class="error-technical-details"></small>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                        <button type="button" class="btn btn-primary">Do something</button>
                    </div>
                </div><!-- /.modal-content -->
            </div><!-- /.modal-dialog -->
        </div><!-- /.modal -->

```
