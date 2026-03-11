# 📁 TS4 Gallery Protobuf Bundle (Recovered)

  ⚠️ All schema definitions contained in this file were originally
  authored by **anadius**.
  This repository exists solely to preserve the protobuf bundle required
  by tools and userscripts that depend on it—in my case, to keep a
  gallery downloader script functional after the original source was
  removed.

------------------------------------------------------------------------

## 📌 About This Repository

This repository hosts a recovered copy of bundle.json / bundle.min.json,
the Protobuf schema used internally by The Sims 4 Gallery / Exchange.
Several community tools—including TS4 gallery downloader
userscripts—cannot function without these message definitions.

The purpose of this repository is not to distribute game content. Its
sole intention is to ensure the continued operation of tools that rely
on these definitions to:

-   Encode / decode .trayitem files
-   Interpret household, lot, and room metadata
-   Handle thumbnails and payloads delivered by the Gallery API

This repository provides only the schema file.

------------------------------------------------------------------------

## 🛠 Why This Repository Exists

The original hosting location for this schema—maintained by anadius—was
removed.
This caused dependent userscripts (including the TS4 Gallery downloader
I personally use) to stop working.

To restore functionality, this recovery mirror was created so that:

-   Existing tools remain compatible
-   Users can continue downloading items directly from the EA Gallery
    website
-   Scripts requiring this resource can function simply by updating the
    resource URL

👉 Recommended TS4 Gallery Downloader

I use and recommend this updated gallery downloader by nrksu1tan:
https://github.com/nrksu1tan/TS4-gallery-downloader

Again: all authorship of the schema belongs to anadius.
This repo simply preserves the file so community tools can continue to
operate.

------------------------------------------------------------------------

## 📦 What This File Contains

The Protobuf schema includes definitions for messages such as:

-   EA.Sims4.Network.TrayMetadata
-   TrayBlueprintMetadata
-   TrayHouseholdMetadata
-   TrayRoomBlueprintMetadata
-   FamilyData
-   ExchangeEnvelope
-   ExchangeSearchResults
-   A variety of enums and nested message structures used by the Gallery
    backend

These definitions are required by tools that use protobuf.js to produce
fully compatible .trayitem and .dat files.

------------------------------------------------------------------------

## ⚠️ Disclaimer

-   This repository does not contain any game assets or copyrighted
    content.
-   It serves only as a preserved schema definition.
-   It does not bypass or replace EA’s Gallery—tools still depend on
    official EA endpoints.
-   This is a purely technical resource required for tool compatibility.
testing changes
