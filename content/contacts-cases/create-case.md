---
title: Creating a case
type: docs
weight: 3
prev: tenants
next: case-detail
---

## What's a case?

A **case** is how we keep track of the process of supporting one household of
tenants with their harassment.

A good way to think of the case is like a **container**. Inside the container
are all of the things that pertain to this tenant's journey through TAHO, which
includes **contacts**, **activities**, and other information.

{{< details title="What's in a case?" closed="true">}}

- **Case Roles**: Links to contacts for
  - the **household** and the household's **tenants**
  - **TAHO staff**
  - **LAHD staff**
  - The **landlord**, **property manager**, or some other **property agent**
    like a cash-for-keys negotiator
  - The **building**
- **Activities** representing events or interactions that occurred, such as:
  - The tenant intake or "warm call"
  - Sending a demand letter to the landlord
  - Gathering evidence of harassment
  - Submitting a TAHO complaint to LAHD
  - All interactions between case contacts
  - Enforcement actions towards the landlord by LAHD
  - ...and more!
- Other important information:
  - The LAHD case number for the TAHO complaint

{{< /details >}}

## Creating a case

The best way to create a new case is to start from the [Tenants
page](https://crm.lataho.org/civicrm/add/tenant). To learn about this page read
the [guide](tenants).

You can create a case for any tenant household by clicking the **Create case
directly** button on the tenant's row in the table.

![tenant-row](/img/tenant-row.jpg)

This will create a new case for the household and begin a **Tenant Intake**
activity. The Tenant Intake, also known as the "warm call", is our initial
meeting with the tenant in which we get to know them and learn about what they
are experiencing.

> [!TIP] Note
> The **Assign Case Intake** allows managers to assign the tenant
> intake to a member of their staff. This process doesn't have its own guide
> yet.

## Tenant Intake

When you create a new case, the first step is always to fill out the intake.
The screen looks like this:

![case-intake](/img/case-intake.jpg)

The intake process is designed to accomplish multiple things:

1. Assign case roles for the tenant household, TAHO staff, building, and landlord
2. Log evidence of harassment that you or the tenant has already gathered
3. Gather additional information about the tenant's experience.

We'll go through each of these steps one-by-one.

## Case Roles

### Household

The first section of the page, labeled **Tenant** is where we designate the
household that this case applies to. If you created the case from the Tenant
page as described above, the tenant household will already be filled out, as
shown in the screen grab above.

> [!TIP] Note
> At this stage, you are also able to add additional tenants to the household. Clicking **Find existing tenant** lets you add a tenant that already exists in the TAHO CRM to the household. Clicking **Add individual tenant** allows you to create a new tenant and adds them to the household. This is the same as creating the tenant on the Tenants page and adding them to the household, as described in the [tenants guide](tenants).

### Building (Property)

Next, you'll add the building that the tenant lives in

This is important for several reasons. First, including the building allows us
to track cases by APN and Council District, which are important to the City.
Second, they allow us to guide our outreach efforts. If one tenant is
experiencing harassment, their neighbors are likely to be experiencing
harassment as well.

Like with tenants and households, we want to prevent duplicate building
records. So, always search for the building using its address. If the building
is not already in the system, you can add it. Over time, as we add more and
more buildings, more will come up in the search, and you won't have to do as
much data entry.

![case-add-building](/img/case-add-building.jpg)

If you need to create a new building, you can do so.

![case-create-building](/img/case-create-building.jpg)

Give the building a name. The best practice is to use the street address as the
name. If the building has an additional well-known name, include it in
parentheses.

Add the building's address. Then, go to [ZIMAS](https://zimas.lacity.org) and
look up the building to get the APN, Council District, RSO (Rent Stabilization
Ordinance) status, and JCO (Just Cause Ordinace) status.

![zimas](/img/zimas.jpg)

Here's where to find each piece of information on ZIMAS:

| Info             | Section                    |
| ---------------- | -------------------------- |
| APN              | Address/Legal Information  |
| Council District | Jurisdictional Information |
| RSO              | Housing                    |
| JCO              | Housing                    |

> [!IMPORTANT] Important
> The building is the same thing as the _parcel_ or the
> _property_. It is _not_ the tenant's individual unit. Your building address
> should **not** include a unit number.

After you have entered the building information, click **Use this Building** to
create the building and add it to the case.

### Landlord

After you have added a building, you can add the landlord. If you added a
building that already exists, and that building already has a landlord
associated with it, it will be auto-filled. If not, you can search for an
existing landlord or add a new one. If you aren't sure, you can skip this step
for now and come back to it later.

> [!TIP] Note
> The landlord section is simplified. When you see the case screen
> later, you will see that you can add different roles, including **Owner** and
> **Property Manager**.

## Evidence

Next is the evidence section. If in your meeting, the tenant is explaining
their harassment situation and providing documentation like photos, videos,
personal testimonials, information about landlord behavior, it's a good idea to
log an evidence activity.

![intake-evidence](/img/intake-evidence.jpg)

Evidence-gathering support is one of our deliverables to LAHD, so it is
important to add a Log Evidence activity each time you support a tenant with
evidence-gathering. In this scenario, we are logging evidence gathering during
the tenant intake, but you will also be able to log evidence as a separate
activity after the intake is complete.

For more information about evidence activities, please read the [Evidence guide](/activities/evidence)

## Intake

The final section of the intake form records information about the results of the intake.

The first two questions, _Finding of tenant harassment?__ and **Tenant agrees
to proceed?** will determine whether this case proceeds or is closed after the
intake. If the answer to both questions is **Yes**, then we will proceed with
supporting the tenant. If the answer is **No** to either, the case will stop.

### Finding of tenant harassment?

**Finding of tenant harassment?** is your call to make. Does it sound like what
the tenant is experiencing is harassment according to TAHO's definition?

### Tenant agrees to proceed?

**Tenant agrees to proceed?** is the tenant's decision. They decide whether or
not they wan to move forward with the next step of the case, which will
typically be a demand letter to the landlord.

### Tenant has already submitted TAHO complaint?

If the tenant is already well into the TAHO process and has submitted their own
complaint, mark **yes**. Doing so will cause this case to work a bit
differently from a typical one, which assumes that you will start with a demand
letter to the landlord, then proceed to an LAHD complaint if the demand letter
is unsuccessful in stopping the harassment.

### Finalizing the intake

To complete the intake, change **Intake status** to **completed**. (If you want
to pause it and come back to it later, mark it **in progress**.)

Add any additional details about this tenant or their case that were not
captured elsewhere to the **Details** area.

Finally, click **Create case & save intake**. This will save the intake
activity and create a new case. The next page you will see will be the case
page for this tenant. Click the next button below to learn more about this
page.
