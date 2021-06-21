# Company Vocabulary

## Data Elements
 * companyId -> identifier = https://schema.org/identifier
 * companyName -> companyName = https://schema.org/legalName (keep local name, point to shared definition)
 * streetAddress -> streetAddress = https://schema.org/streetAddress
 * city -> city = https://schema.org/addressLocality (keep local name, point to shared definition)
 * stateProvince -> addressRegion = https://schema.org/addressRegion
 * postalCode -> postalCode = https://schema.org/postalCode
 * country -> addressCountry = https://schema.org/addressCountry
 * telephone -> telephone = https://schema.org/telephone
 * email -> email = https://schema.org/email
 * status (suspended, active, pending,closed) -> status = https://api.mamund.com/terms/status (point to local definition)
 * dateCreated -> dateCreated = https://schema.org/dateCreated
 * dateUpdated -> dateModified = https://schema.org/dateModified

## Action Elements
 
 * list
 * create
   * legalName[R], streetAddress, locality, addressRegion, postalCode, 
      addressCountry(US), telephone, email[R], status(pending)[R]
 * read
   * identifier[R]
 * update
   * identifier[R], legalName[R], streetAddress, locality, addressRegion, 
      postalCode, addressCountry(US), telephone, email[R], status[R]
 * delete
   * identifier[R]
 * filter 
   * status, addressCountry, addressRegion, legalName

