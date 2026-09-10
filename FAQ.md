# Beacon

## BEACON-001 — APP Buttons Cannot Be Clicked

**Q: What should I do if some APP buttons cannot be clicked or the page layout is incorrect?**

**A:** If you encounter this issue, please try using an older version of the APP.

Older versions have been published on GitHub and can be downloaded from the corresponding release page.

We recommend using **APP V3.7 or later**.

The latest APP version can be downloaded through GitHub or the Google Play Store.


---

## BEACON-002 — Connecting Beacon to a Phone or Computer

**Q: Can I connect the Beacon directly to a phone or computer?**

**A:** Beacon devices mainly transmit data through **BLE advertising** and do not support direct communication through the standard Bluetooth interface of a phone or computer.

If you need to configure Beacon parameters, please use the APP provided by our company.


---

## BEACON-003 — Home Assistant Compatibility

**Q: Can the CP27/CP35 be used with Home Assistant?**

**A:** Yes. **CP27/CP35 supports use with Home Assistant.**

Our engineering team may provide a related tutorial in the future.


---

## BEACON-004 — SDK Availability

**Q: Do you provide an application SDK for the Beacon devices?**

**A:** Please note that we currently offer an SDK for mobile applications, not for firmware; please do not confuse the two.

In most use cases, Beacon devices do not require a complex SDK, as their primary function is to broadcast BLE advertising packets. Developers simply need to scan for these packets and parse the data according to standard Beacon advertising formats.

For bulk orders, if you have specific configuration requirements, we can pre-configure the Beacon devices to your specifications prior to shipment.

If you require a software SDK for commercial applications or independent development, please contact our customer service team.
