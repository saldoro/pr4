# Prisma4 Web Vocabulary

**Version:** 1.1 *(draft)*  
**Working version:** January 2026  
**Editor:** Salvador Domenech

- **This version:** https://github.com/saldoro/pr4/v1.1/
- **Latest version:** https://github.com/saldoro/pr4/


## Abstract

The **Prisma4 Web Vocabulary** compiles terms defined in various standards and
data systems (GS1 Web Vocabulary, Schema.org, etc.) and will be available for
general use following the principles of **Linked Data**.

The initial focus of Prisma4 is on the classes and properties common to all
items or products used in **industrial maintenance**.


## Table of Contents

- [Classes](#classes)
  - [0100 Item](#0100-item)
  - [0200 Manufacturer](#0200-manufacturer)
  - [0300 Supplier](#0300-supplier)
- [Properties](#properties)
  - [0101 Item Identifier](#0101-item-identifier)
  - [0102 GTIN](#0102-gtin)


## Classes

### 0100 Item

**Description**

Any item or product for which specific information needs to be retrieved.  
An *Item* (article, product, goods item, object) is the smallest unit managed
as an entity within the Prisma® 4 system.

It represents any material, spare part, consumable or element acquired and
stored in the supplies warehouse, usable in construction and maintenance work
by internal and external operators.

| Field | Value |
|------|-------|
| **URI** | https://github.com/saldoro/pr4/v1.1/0100_Item |
| **Superclass** | |
| **Subclasses** | |
| **Related properties** | |
| **Example values** | |

[Back to top](#prisma4-web-vocabulary)


### 0200 Manufacturer

**Description**

Organization that produces the Item.  
The Manufacturer may also supply its own products, in which case it should also
be included under **Suppliers**.

| Field | Value |
|------|-------|
| **URI** | https://github.com/saldoro/pr4/1.1/0200_Manufacturer |
| **Superclass** | |
| **Subclasses** | |
| **Related properties** | |
| **Example values** | |

[Back to top](#prisma4-web-vocabulary)


### 0300 Supplier

**Description**

Organization that supplies, distributes, provides, or sells the Item.

| Field | Value |
|------|-------|
| **URI** | https://github.com/saldoro/pr4/1.1/0300_Supplier |
| **Superclass** | |
| **Subclasses** | |
| **Related properties** | |
| **Example values** | |

[Back to top](#prisma4-web-vocabulary)


## Properties

### 0101 Item Identifier

**Description**

This property.

| Field | Value |
|------|-------|
| **URI** | https://github.com/saldoro/pr4/v1.1/0101_itemID |
| **Domain** | |
| **Range** | |
| **Superproperty of** | |
| **Inverse** | |
| **Example values** | |

[Back to top](#prisma4-web-vocabulary)


### 0102 GTIN

**Description**

This property.

| Field | Value |
|------|-------|
| **URI** | https://github.com/saldoro/pr4/v1.1/0102_gtin |
| **Domain** | |
| **Range** | |
| **Superproperty of** | |
| **Example values** | |

[Back to top](#prisma4-web-vocabulary)


