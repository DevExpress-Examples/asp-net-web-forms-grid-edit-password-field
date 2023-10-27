<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2012)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Grid View for ASP.NET Web Forms - How to edit a password field
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e2012/)**
<!-- run online end -->

This example demonstrates one of possible ways to edit a password field.

![](grid-with-popup-to-edit-password-field.png)

## Implementation Details

According to the security settings which are implemented in our editors, the password can't be set on the server side. In edit mode, an editor with enabled the [Password](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxTextBoxBase.Password) property is displayed empty. Since it might confuse users, we suggest you to implement the following functionality to edit a password field.

## Files to Review

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
