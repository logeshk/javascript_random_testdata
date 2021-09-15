# Generate Random & Massive Testdata in JavaScript framework on the browser and node.js

# Prerequisite
Add faker.js on package json dependencies ("faker": "^4.1.0")

# sample code to generate random EmailId Steps
On spec file inside describe function add
var randomEmail = require('faker');
var EmailId

On It block, respective place
EmailId = "TestEmail" + randomnumber.random.number() + "@gmail.com";

Thats It, Now you can pass Random EmailId on required It block
Below API methods almost cover most of web application required test data generation,

# address
zipCode
zipCodeByState
city
cityPrefix
citySuffix
cityName
streetName
streetAddress
streetSuffix
streetPrefix
secondaryAddress
county
country
countryCode
state
stateAbbr
latitude
longitude
direction
cardinalDirection
ordinalDirection
nearbyGPSCoordinate
timeZone
# animal
dog
cat
snake
bear
lion
cetacean
horse
bird
cow
fish
crocodilia
insect
rabbit
type
# commerce
color
department
productName
price
productAdjective
productMaterial
product
productDescription
company
suffixes
# companyName
companySuffix
catchPhrase
bs
catchPhraseAdjective
catchPhraseDescriptor
catchPhraseNoun
bsAdjective
bsBuzz
bsNoun
# database
column
type
collation
engine
datatype
number
float
datetime
string
uuid
boolean
hexaDecimal
json
array
# date
past
future
between
betweens
recent
soon
month
weekday
# finance
account
accountName
routingNumber
mask
amount
transactionType
currencyCode
currencyName
currencySymbol
bitcoinAddress
litecoinAddress
creditCardNumber
creditCardCVV
ethereumAddress
iban
bic
transactionDescription
# git
branch
commitEntry
commitMessage
commitSha
shortSha
# hacker
abbreviation
adjective
noun
verb
ingverb
phrase
# helpers
randomize
slugify
replaceSymbolWithNumber
replaceSymbols
replaceCreditCardSymbols
repeatString
regexpStyleStringParse
shuffle
mustache
createCard
contextualCard
userCard
createTransaction
# image
image
avatar
imageUrl
abstract
animals
business
cats
city
food
nightlife
fashion
people
nature
sports
technics
transport
dataUri
lorempixel
unsplash
lorempicsum
# internet
avatar
email
exampleEmail
userName
protocol
httpMethod
url
domainName
domainSuffix
domainWord
ip
ipv6
port
userAgent
color
mac
password
# lorem
word
words
sentence
slug
sentences
paragraph
paragraphs
text
lines
# mersenne
rand
seed
seed_array
# music
genre
# name
firstName
lastName
middleName
findName
jobTitle
gender
prefix
suffix
title
jobDescriptor
jobArea
jobType
# phone
phoneNumber
phoneNumberFormat
phoneFormats
# random
number
float
arrayElement
arrayElements
objectElement
uuid
boolean
word
words
image
locale
alpha
alphaNumeric
hexaDecimal
# system
fileName
commonFileName
mimeType
commonFileType
commonFileExt
fileType
fileExt
directoryPath
filePath
semver
# time
recent
# unique
# vehicle
vehicle
manufacturer
model
type
fuel
vin
color
vrm
bicycle

Reference : https://www.npmjs.com/package/faker
