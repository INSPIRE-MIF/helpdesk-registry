## Guidelines for change proposals

When you provide a change proposal, remember to specify all the required information in order to facilitate the correct evaluation and eventual implementation of the proposed changes.

Please follow the instructions below as closely as possible to give the Control Body all the relevant information to take a decision and to facilitate the update by the register manager.

### Description

Here you should describe:
-   the **URI** of the register/reference code. This field should contain the URI of the item to be updated or the new URI in case of addition proposal. In case the change is related to more than one item, complete this field with the register URI or the collection URI and specify each URI in the body of the proposal. 
    -   Example - [http://inspire.ec.europa.eu/theme/ad](http://inspire.ec.europa.eu/theme/ad) (an item)
    - Example - [http://inspire.ec.europa.eu/media-types/application](http://inspire.ec.europa.eu/media-types/application) (a collection of items)
-   the **rationale**, motivation and/or use case behind the proposal to be addressed, including any relevant information that could help the Control Body to take a decision, and  the
    
-   **proposed change(s)**, described as concretely as possible (please specify all the relevant information, including eventual translations, related to your proposal)   
-   The **type** of change:
    -   *Addition*: to propose the addition of a new item to a register or to an existing code list or to propose a new register
    -   *Clarification*: to propose a change to an existing item
    -   *Supersession*: to propose a register item to be retired and replaced by one or more new items
    -   *Invalidation*: to propose to invalidate a register item that has a substantive error, and (optionally) replace it with another item (or items).
    -   *Retirement*: to propose to retire an item that is no longer useful for producing data.
 
#### Example 1
**URI**: https://inspire.ec.europa.eu/theme/ad
**Motivation**: The definition of the theme AD needs to be updated because it has a typo in the description for the French language.
**Proposed change**: Change definition from "Localisation des prétés  fondée sur les ideniants des adresses, habient le nom de la rue, le numéro de la maon et le code postal" to "Localisation des propriétés  fondée sur les identifiants des adresses, habituellement le nom de la rue, le numéro de la maison et le code postal."
**Change type**: Clarification

#### Example 2
**URI**: https://inspire.ec.europa.eu/media-types
**Motivation**:  We propose to add some items in the media-types register because we need some missing codes to represent the media-types of our data.
**Proposed changes**: new proposed items under the media-types/application
-   GeoJSON

    Register: [http://inspire.ec.europa.eu/media-types](http://inspire.ec.europa.eu/media-types) Label: application/vnd.geo+jsonDefinition: The media type shall be used for the GeoJSON file format.
    URI: [https://www.iana.org/assignments/media-types/application/vnd.geo+json](https://www.iana.org/assignments/media-types/application/vnd.geo+json) External value: true

-   GPX    

    Register: [http://inspire.ec.europa.eu/media-types](http://inspire.ec.europa.eu/media-types)Label: application/gpx+xmlDefinition: The media type shall be used for the GPX file format.URI: [http://inspire.ec.europa.eu/media-types/application/geo+json](http://inspire.ec.europa.eu/media-types/application/geo+json) External value: false

**Change type**: addition
