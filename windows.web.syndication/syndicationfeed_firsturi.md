---
-api-id: P:Windows.Web.Syndication.SyndicationFeed.FirstUri
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Uri FirstUri { get; }
-->

# Windows.Web.Syndication.SyndicationFeed.FirstUri

## -description
Gets the first Uniform Resource Identifier (URI) in a sequence. This property represents the **atom:link** element with attribute **rel=”first”**.

## -property-value
The **atom:link** element with attribute **rel="first"**. This property is the absolute Uniform Resource Identifier (URI) resolved against the **xml:base** attribute, if it is present. If the **href** attribute is a relative Uniform Resource Identifier (URI) string and there is no **xml:base** attribute, this property will be null because the relative Uniform Resource Identifier (URI) is not supported by the runtime Uniform Resource Identifier (URI) class.

## -remarks

## -examples

## -see-also
