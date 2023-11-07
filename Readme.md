<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128533940/15.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2012)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Grid View for ASP.NET Web Forms - How to edit a password field
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/128533940/)**
<!-- run online end -->

This example demonstrates one of possible ways to edit a password field.

![](grid-with-popup-to-edit-password-field.png)

## Implementation Details

According to the security settings implemented in our editors, the password cannot be set on the server side. In edit mode, an editor with an enabled [Password](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxTextBoxBase.Password) property is displayed empty. Since this can confuse users, we suggest that you implement the following functionality to edit a password field:

## Files to Review

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
