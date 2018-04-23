# How to fill values in a new row obtained from the row where the "new" button was clicked


<p>Rows are filled in the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridViewASPxGridView_InitNewRowtopic">ASPxGridView.InitNewRow</a> event handler. Editing starts by performing a callback on the client side with an appropriate parameter "New|#", where "#" is a row number where the "new" button is placed. The <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridViewASPxGridView_CustomCallbacktopic">ASPxGridView.CustomCallback</a> event handler performs parsing and new node inserting. The default values are added to the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebDataASPxDataInitNewRowEventArgs_NewValuestopic">e.NewValues</a> argument.</p><p><strong>Note:</strong><br />
The database couldn't be updated in the example due to server restrictions.</p>

<br/>

