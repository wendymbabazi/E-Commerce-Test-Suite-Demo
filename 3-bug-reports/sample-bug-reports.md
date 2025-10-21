# Sample Bug Reports - Jumia Uganda

## Bug 1: MTN Mobile Money Timeout
**Title:** MTN Mobile Money payment fails during peak hours (4-6 PM)

**Description:** 
When attempting Mobile Money payments between 4-6 PM, transaction times out frequently. This coincides with network congestion hours in Kampala.

**Steps to Reproduce:**
1. Add any product to cart
2. Select MTN Mobile Money payment
3. Attempt payment between 4-6 PM
4. Observe timeout after 2 minutes

**Expected:** Payment processes within 30 seconds
**Actual:** Payment times out after 2 minutes
**Network:** MTN Uganda, 3G connection

**Impact:** High - Prevents purchases during evening shopping hours
