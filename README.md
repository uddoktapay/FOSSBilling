## UddoktaPay Integration for FOSSBilling

### Installation Steps

**Step 1:** Upload (or replace) the `ipn.php` file in the **root directory** of your FOSSBilling installation:

```
FOSSBilling_Path/ipn.php
```

**Step 2:** Copy the entire `UddoktaPay` folder into the following directory:

```
FOSSBilling_Path/library/Payment/Adapter
```

Your directory structure should look like this:

```
FOSSBilling_Path/library/Payment/Adapter/UddoktaPay/UddoktaPay.php
FOSSBilling_Path/library/Payment/Adapter/UddoktaPay/UddoktaPay.png
```

That’s it! Your **UddoktaPay** integration for **FOSSBilling** is now ready to use.