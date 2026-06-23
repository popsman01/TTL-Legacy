# Created Issues

| Issue # | Title | GitHub URL |
|---------|-------|------------|
| #1 | Add `get_vault_age` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/766 |
| #2 | Enforce Maximum Number of Vaults Per Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/767 |
| #3 | Add `is_hibernating` Convenience Query | https://github.com/TTL-Legacy/TTL-Legacy/issues/768 |
| #4 | Validate `check_in_interval` Upper Bound Against Soroban Max TTL | https://github.com/TTL-Legacy/TTL-Legacy/issues/769 |
| #5 | Implement `batch_deposit` Atomicity Guarantee | https://github.com/TTL-Legacy/TTL-Legacy/issues/770 |
| #6 | Add `get_check_in_history_page` with Cursor Pagination | https://github.com/TTL-Legacy/TTL-Legacy/issues/771 |
| #7 | Prevent Owner Self-Assignment as Beneficiary on `update_beneficiary` | https://github.com/TTL-Legacy/TTL-Legacy/issues/772 |
| #8 | Emit Event When Vault Balance Drops to Zero | https://github.com/TTL-Legacy/TTL-Legacy/issues/773 |
| #9 | Add `get_vault_summary` Returning Key Fields in One Call | https://github.com/TTL-Legacy/TTL-Legacy/issues/774 |
| #10 | Reject Deposits into Cancelled Vaults | https://github.com/TTL-Legacy/TTL-Legacy/issues/775 |
| #11 | Add Minimum TTL Remaining Warning Event | https://github.com/TTL-Legacy/TTL-Legacy/issues/776 |
| #12 | Implement `get_next_check_in_deadline` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/777 |
| #13 | Enforce Minimum Gap Between Consecutive Check-Ins | https://github.com/TTL-Legacy/TTL-Legacy/issues/778 |
| #14 | Record TTL Extension Amount in Check-In Event | https://github.com/TTL-Legacy/TTL-Legacy/issues/779 |
| #15 | Fix: `exit_hibernation` Does Not Re-Extend Vault TTL | https://github.com/TTL-Legacy/TTL-Legacy/issues/780 |
| #16 | Add `get_streak_summary` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/781 |
| #17 | Enforce Maximum Number of Passkeys Per Vault | https://github.com/TTL-Legacy/TTL-Legacy/issues/782 |
| #18 | Add `list_passkeys` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/783 |
| #19 | Reject `add_passkey` with Duplicate Hash | https://github.com/TTL-Legacy/TTL-Legacy/issues/784 |
| #20 | Implement Passkey Last-Used Timestamp Tracking | https://github.com/TTL-Legacy/TTL-Legacy/issues/785 |
| #21 | Add `get_beneficiary_count` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/786 |
| #22 | Validate Total BPS Equals 10000 on Each `set_beneficiaries` Call | https://github.com/TTL-Legacy/TTL-Legacy/issues/787 |
| #23 | Add Grace Period for Expired-But-Unclaimed Release | https://github.com/TTL-Legacy/TTL-Legacy/issues/788 |
| #24 | Implement `get_release_conditions` Query | https://github.com/TTL-Legacy/TTL-Legacy/issues/789 |
| #25 | Prevent `trigger_release` When Vault Is Paused | https://github.com/TTL-Legacy/TTL-Legacy/issues/790 |
| #26 | Add `set_release_memo` for On-Chain Inheritance Notes | https://github.com/TTL-Legacy/TTL-Legacy/issues/791 |
| #27 | Fix: `partial_release` Does Not Verify Caller Is Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/792 |
| #28 | Emit Event When Beneficiary Conflict Auto-Expires | https://github.com/TTL-Legacy/TTL-Legacy/issues/793 |
| #29 | Validate Beneficiary Address Is Not Zero Address | https://github.com/TTL-Legacy/TTL-Legacy/issues/794 |
| #30 | Add `get_unconditional_release_time` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/795 |
| #31 | Add `list_open_proposals` for a Vault | https://github.com/TTL-Legacy/TTL-Legacy/issues/796 |
| #32 | Enforce Minimum Signers Threshold Is at Least 1 | https://github.com/TTL-Legacy/TTL-Legacy/issues/797 |
| #33 | Implement Multi-Sig Proposal Veto by Single Signer | https://github.com/TTL-Legacy/TTL-Legacy/issues/798 |
| #34 | Add Multi-Sig Signer Removal Without Full Reconfiguration | https://github.com/TTL-Legacy/TTL-Legacy/issues/799 |
| #35 | Require Multi-Sig Approval for Vault Cancellation When Multi-Sig Is Active | https://github.com/TTL-Legacy/TTL-Legacy/issues/800 |
| #36 | Add `get_total_unvested_amount` Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/801 |
| #37 | Enforce Vesting Schedule End Date Is After Start Date | https://github.com/TTL-Legacy/TTL-Legacy/issues/802 |
| #38 | Add `cancel_vesting_schedule` for Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/803 |
| #39 | Fix: `claim_vested` Does Not Check Vault Is Not Cancelled | https://github.com/TTL-Legacy/TTL-Legacy/issues/804 |
| #40 | Add `get_vesting_schedule_count` Per Vault | https://github.com/TTL-Legacy/TTL-Legacy/issues/805 |
| #41 | Add `cancel_ownership_transfer` by New Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/806 |
| #42 | Emit Event When Ownership Transfer Timelock Expires Without Acceptance | https://github.com/TTL-Legacy/TTL-Legacy/issues/807 |
| #43 | Prevent Ownership Transfer to Current Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/808 |
| #44 | Implement Two-Step Protocol Configuration Update | https://github.com/TTL-Legacy/TTL-Legacy/issues/809 |
| #45 | Add `get_protocol_config` Query Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/810 |
| #46 | Enforce Admin Address Cannot Be a Vault Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/811 |
| #47 | Add `get_admin` Query Function | https://github.com/TTL-Legacy/TTL-Legacy/issues/812 |
| #48 | Implement Admin Transfer with Timelock | https://github.com/TTL-Legacy/TTL-Legacy/issues/813 |
| #49 | Add Contract Pause Reason Tracking | https://github.com/TTL-Legacy/TTL-Legacy/issues/814 |
| #50 | Validate `initialize` Cannot Be Called with Expired-Looking Timestamps | https://github.com/TTL-Legacy/TTL-Legacy/issues/815 |
| #51 | Replace ZK Verifier Stub with Groth16 Verification Logic | https://github.com/TTL-Legacy/TTL-Legacy/issues/816 |
| #52 | Add `verify_claim` Input Size Limits | https://github.com/TTL-Legacy/TTL-Legacy/issues/817 |
| #53 | Emit an Event from `verify_claim` for Audit Purposes | https://github.com/TTL-Legacy/TTL-Legacy/issues/818 |
| #54 | Add Request Body Size Limit Middleware | https://github.com/TTL-Legacy/TTL-Legacy/issues/819 |
| #55 | Implement Structured Error Responses Across All Handlers | https://github.com/TTL-Legacy/TTL-Legacy/issues/820 |
| #56 | Add Health Check Endpoint | https://github.com/TTL-Legacy/TTL-Legacy/issues/821 |
| #57 | Implement Database Connection Pool Size Configuration | https://github.com/TTL-Legacy/TTL-Legacy/issues/822 |
| #58 | Add CORS Configuration to Backend | https://github.com/TTL-Legacy/TTL-Legacy/issues/823 |
| #59 | Fix: `scheduler.rs` Does Not Handle Database Errors Gracefully | https://github.com/TTL-Legacy/TTL-Legacy/issues/824 |
| #60 | Add Idempotency Key Support for Reminder Creation | https://github.com/TTL-Legacy/TTL-Legacy/issues/825 |
| #61 | Add Notification Deduplication Window | https://github.com/TTL-Legacy/TTL-Legacy/issues/826 |
| #62 | Implement Notification Channel Priority Fallback | https://github.com/TTL-Legacy/TTL-Legacy/issues/827 |
| #63 | Add Unsubscribe Link in Reminder Emails | https://github.com/TTL-Legacy/TTL-Legacy/issues/828 |
| #64 | Implement Notification Retry Budget | https://github.com/TTL-Legacy/TTL-Legacy/issues/829 |
| #65 | Add Email Template Internationalization Support | https://github.com/TTL-Legacy/TTL-Legacy/issues/830 |
| #66 | Add WebSocket Heartbeat / Ping-Pong | https://github.com/TTL-Legacy/TTL-Legacy/issues/831 |
| #67 | Implement WebSocket Authentication | https://github.com/TTL-Legacy/TTL-Legacy/issues/832 |
| #68 | Add WebSocket Message Rate Limiting | https://github.com/TTL-Legacy/TTL-Legacy/issues/833 |
| #69 | Add Database Migration Version Tracking Table | https://github.com/TTL-Legacy/TTL-Legacy/issues/834 |
| #70 | Implement Soft Delete for Vault Reminder Records | https://github.com/TTL-Legacy/TTL-Legacy/issues/835 |
| #71 | Implement Biometric Prompt Before Check-In on Android | https://github.com/TTL-Legacy/TTL-Legacy/issues/836 |
| #72 | Add Offline Check-In Queuing for Android | https://github.com/TTL-Legacy/TTL-Legacy/issues/837 |
| #73 | Implement Deep Link Handling for Beneficiary Acceptance on Android | https://github.com/TTL-Legacy/TTL-Legacy/issues/838 |
| #74 | Add Push Notification Permission Request Flow on Android | https://github.com/TTL-Legacy/TTL-Legacy/issues/839 |
| #75 | Implement Vault Status Widget for Android Home Screen | https://github.com/TTL-Legacy/TTL-Legacy/issues/840 |
| #76 | Add Face ID / Touch ID Authentication Before Check-In on iOS | https://github.com/TTL-Legacy/TTL-Legacy/issues/841 |
| #77 | Implement iOS Lock Screen Widget (WidgetKit) | https://github.com/TTL-Legacy/TTL-Legacy/issues/842 |
| #78 | Add Universal Link Handling for Vault Invitations on iOS | https://github.com/TTL-Legacy/TTL-Legacy/issues/843 |
| #79 | Implement Background Refresh for TTL Monitoring on iOS | https://github.com/TTL-Legacy/TTL-Legacy/issues/844 |
| #80 | Add iCloud Keychain Backup Option for Passkey Metadata on iOS | https://github.com/TTL-Legacy/TTL-Legacy/issues/845 |
| #81 | Add Fuzz Testing for Vesting Schedule Calculation | https://github.com/TTL-Legacy/TTL-Legacy/issues/846 |
| #82 | Add Invariant Tests for BPS Sum After Multi-Beneficiary Operations | https://github.com/TTL-Legacy/TTL-Legacy/issues/847 |
| #83 | Add Integration Test: Full Vault Lifecycle on Local Soroban | https://github.com/TTL-Legacy/TTL-Legacy/issues/848 |
| #84 | Add Property-Based Tests for TTL Extension Calculation | https://github.com/TTL-Legacy/TTL-Legacy/issues/849 |
| #85 | Add Negative Tests for All `ContractError` Variants | https://github.com/TTL-Legacy/TTL-Legacy/issues/850 |
| #86 | Add Tests for Backend `notifications.rs` Email and SMS Delivery | https://github.com/TTL-Legacy/TTL-Legacy/issues/851 |
| #87 | Add Load Test for `trigger_release` with 50-Beneficiary Vault | https://github.com/TTL-Legacy/TTL-Legacy/issues/852 |
| #88 | Add Regression Test for Vault ID Uniqueness Under Concurrent Creation | https://github.com/TTL-Legacy/TTL-Legacy/issues/853 |
| #89 | Add `docs/zk-verifier.md` Explaining the Stub and Migration Path | https://github.com/TTL-Legacy/TTL-Legacy/issues/854 |
| #90 | Add `docs/multi-sig.md` Update with Veto and Signer Removal | https://github.com/TTL-Legacy/TTL-Legacy/issues/855 |
| #91 | Create `docs/backend-api.md` with Full Endpoint Reference | https://github.com/TTL-Legacy/TTL-Legacy/issues/856 |
| #92 | Add `docs/mobile-passkey-flow.md` for iOS and Android | https://github.com/TTL-Legacy/TTL-Legacy/issues/857 |
| #93 | Add `docs/token-management.md` Section on Fee Calculation | https://github.com/TTL-Legacy/TTL-Legacy/issues/858 |
| #94 | Create OpenAPI Specification for Backend | https://github.com/TTL-Legacy/TTL-Legacy/issues/859 |
| #95 | Add `cargo audit` to CI Pipeline | https://github.com/TTL-Legacy/TTL-Legacy/issues/860 |
| #96 | Add Dependabot Configuration for Rust and GitHub Actions | https://github.com/TTL-Legacy/TTL-Legacy/issues/861 |
| #97 | Add Docker Compose Setup for Local Development | https://github.com/TTL-Legacy/TTL-Legacy/issues/862 |
| #98 | Implement Contract Deployment Idempotency Check in Deploy Scripts | https://github.com/TTL-Legacy/TTL-Legacy/issues/863 |
| #99 | Add Contract WASM Size Check to CI | https://github.com/TTL-Legacy/TTL-Legacy/issues/864 |
| #100 | Implement Automated Testnet Smoke Test in CI | https://github.com/TTL-Legacy/TTL-Legacy/issues/865 |
| #101 | Implement Replay Attack Prevention for Check-In Delegation | https://github.com/TTL-Legacy/TTL-Legacy/issues/866 |
| #102 | Add Rate Limiting for `trigger_release` Calls | https://github.com/TTL-Legacy/TTL-Legacy/issues/867 |
| #103 | Implement Withdrawal Destination Validation Against Vault Owner | https://github.com/TTL-Legacy/TTL-Legacy/issues/868 |
| #104 | Add Secret Storage Audit for `.env` Files in CI | https://github.com/TTL-Legacy/TTL-Legacy/issues/869 |
| #105 | Implement Emergency Vault Freeze by Admin | https://github.com/TTL-Legacy/TTL-Legacy/issues/870 |
| #106 | Add Input Sanitization for Metadata `Bytes` Fields | https://github.com/TTL-Legacy/TTL-Legacy/issues/871 |
| #107 | Benchmark `trigger_release` Instruction Usage vs. Beneficiary Count | https://github.com/TTL-Legacy/TTL-Legacy/issues/872 |
| #108 | Optimize `get_check_in_history_page` to Avoid Full Deserialization | https://github.com/TTL-Legacy/TTL-Legacy/issues/873 |
| #109 | Implement Lazy TTL Extension to Avoid Per-Read Storage Writes | https://github.com/TTL-Legacy/TTL-Legacy/issues/874 |
| #110 | Add `make` / Task Runner Targets for Common Development Commands | https://github.com/TTL-Legacy/TTL-Legacy/issues/875 |
| #111 | Add VS Code `launch.json` for Rust Contract Debugging | https://github.com/TTL-Legacy/TTL-Legacy/issues/876 |
| #112 | Add `clippy` Lint Configuration File | https://github.com/TTL-Legacy/TTL-Legacy/issues/877 |
| #113 | Add `rustfmt` Configuration File | https://github.com/TTL-Legacy/TTL-Legacy/issues/878 |
| #114 | Create `ARCHITECTURE.md` Top-Level Overview Document | https://github.com/TTL-Legacy/TTL-Legacy/issues/879 |
| #115 | Add `CHANGELOG.md` and Semantic Versioning Policy | https://github.com/TTL-Legacy/TTL-Legacy/issues/880 |
| #116 | Add Example `.env` Values for All Mobile Configuration Variables | https://github.com/TTL-Legacy/TTL-Legacy/issues/881 |
| #117 | Implement Contract Version Compatibility Check on Backend Startup | https://github.com/TTL-Legacy/TTL-Legacy/issues/882 |

---

# 117 Unsolved Issues for TTL-Legacy

## Smart Contract — Vault Core

### 1. Add `get_vault_age` Function
**Labels:** `enhancement`, `vault-core`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
There is no way to query how long a vault has been active. Callers must compute `current_time - vault.created_at` externally, which requires fetching the full vault struct.

**Tasks:**
- Implement `get_vault_age(env, vault_id) -> u64` returning seconds since creation
- Return `0` if the vault does not exist
- Add tests for newly-created and long-lived vaults

---

### 2. Enforce Maximum Number of Vaults Per Owner
**Labels:** `enhancement`, `security`, `vault-core`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
A single owner can create an unbounded number of vaults, which bloats the `OwnerVaults` index and can exhaust ledger storage.

**Tasks:**
- Add `max_vaults_per_owner: u32` to `ProtocolConfig` (default 50)
- Reject `create_vault` when the owner already holds `max_vaults_per_owner` vaults
- Emit a descriptive error `VaultLimitReached`
- Add tests for limit enforcement and limit update

---

### 3. Add `is_hibernating` Convenience Query
**Labels:** `enhancement`, `vault-core`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
Callers must call `get_hibernation` and check for `Some` to determine hibernation state. A dedicated boolean query simplifies off-chain integrations.

**Tasks:**
- Implement `is_hibernating(env, vault_id) -> bool`
- Return `true` iff a non-expired `HibernationEntry` exists for the vault
- Add tests for hibernating, non-hibernating, and expired hibernation states

---

### 4. Validate `check_in_interval` Upper Bound Against Soroban Max TTL
**Labels:** `bug`, `vault-core`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
The contract enforces a configurable `max_check_in_interval`, but does not verify that the derived TTL in ledgers stays within `MAX_PERSISTENT_TTL` (3,110,400 ledgers ≈ 180 days). A very large interval silently wraps or is clamped inconsistently.

**Tasks:**
- In `create_vault` and `update_check_in_interval`, assert `vault_ttl_ledgers(interval) <= MAX_PERSISTENT_TTL`
- Return `ContractError::IntervalTooHigh` when the computed TTL would exceed the cap
- Add tests for the boundary value

---

### 5. Implement `batch_deposit` Atomicity Guarantee
**Labels:** `bug`, `vault-core`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
`batch_deposit` processes vaults sequentially. If the token transfer for vault N succeeds but vault N+1 panics, the first transfers are non-refundable and the batch is left in a partially-executed state.

**Tasks:**
- Pre-validate all vaults and amounts before issuing any token transfers
- Return `ContractError::BatchPartialFailure` with the failing index if pre-validation fails
- Add tests confirming no transfers occur when any vault in the batch is invalid

---

### 6. Add `get_check_in_history_page` with Cursor Pagination
**Labels:** `enhancement`, `vault-core`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
`CheckInHistory` entries accumulate over the vault lifetime. Returning the full list in one call can hit Soroban's instruction limit for long-lived vaults.

**Tasks:**
- Implement `get_check_in_history_page(env, vault_id, cursor: u64, limit: u32) -> Vec<CheckInHistoryEntry>`
- `cursor` is the index of the first entry to return; `0` = most recent
- Cap `limit` at 50
- Add tests for pagination, boundary conditions, and empty history

---

### 7. Prevent Owner Self-Assignment as Beneficiary on `update_beneficiary`
**Labels:** `bug`, `vault-core`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
`set_beneficiaries` rejects the owner appearing in the list, but `update_beneficiary` (single-beneficiary path) does not perform this check.

**Tasks:**
- Add `require(new_beneficiary != vault.owner)` in `update_beneficiary`
- Return `ContractError::OwnerCannotBeBeneficiary`
- Add a test asserting the error is returned

---

### 8. Emit Event When Vault Balance Drops to Zero
**Labels:** `enhancement`, `vault-core`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
There is no on-chain signal when a vault's balance reaches zero after a withdrawal. Off-chain monitors must poll to detect empty vaults.

**Tasks:**
- Add `VAULT_EMPTY_TOPIC: Symbol = symbol_short!("v_empty")`
- Emit the event from `withdraw` when `vault.balance == 0` after transfer
- Add a test asserting the event is emitted exactly once at zero balance

---

### 9. Add `get_vault_summary` Returning Key Fields in One Call
**Labels:** `enhancement`, `vault-core`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
Frontends typically need `balance`, `status`, `ttl_remaining`, and `beneficiary` together. Currently four separate calls are required, quadrupling RPC round-trips.

**Tasks:**
- Define `VaultSummary { balance, status, ttl_remaining, beneficiary, is_hibernating }` in `types.rs`
- Implement `get_vault_summary(env, vault_id) -> VaultSummary`
- Add tests for active, expired, and hibernating vaults

---

### 10. Reject Deposits into Cancelled Vaults
**Labels:** `bug`, `vault-core`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
`deposit` checks for `AlreadyReleased` but not for `Cancelled` status. A cancelled vault can still receive deposits, permanently locking funds.

**Tasks:**
- Add `ReleaseStatus::Cancelled` guard in `deposit`
- Return `ContractError::VaultCancelled`
- Add a test confirming deposit is rejected after cancellation

---

## Smart Contract — TTL & Check-In

### 11. Add Minimum TTL Remaining Warning Event
**Labels:** `enhancement`, `ttl`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
`ping_expiry` emits an event but only when called explicitly. There is no automatic on-chain warning when the TTL drops below a configurable threshold during check-in or deposit.

**Tasks:**
- Add `TTL_WARNING_TOPIC: Symbol = symbol_short!("ttl_warn")`
- Emit `TTL_WARNING_TOPIC` at the end of `check_in` if remaining TTL < `EXPIRY_WARNING_THRESHOLD`
- Add tests for threshold boundary (just above, at, just below)

---

### 12. Implement `get_next_check_in_deadline` Function
**Labels:** `enhancement`, `ttl`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Callers must compute `vault.last_check_in + vault.check_in_interval` manually. A dedicated function reduces off-chain logic and can account for hibernation correctly.

**Tasks:**
- Implement `get_next_check_in_deadline(env, vault_id) -> Option<u64>`
- Return `None` if the vault is hibernating or already expired
- Return the absolute timestamp of the next required check-in otherwise
- Add tests for normal, hibernating, and expired states

---

### 13. Enforce Minimum Gap Between Consecutive Check-Ins
**Labels:** `enhancement`, `ttl`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
An owner can call `check_in` hundreds of times per ledger to artificially inflate the streak counter or stress-test the chain. A per-vault cooldown prevents spam.

**Tasks:**
- Add `min_check_in_cooldown_seconds: u64` to `ProtocolConfig` (default 60)
- Reject `check_in` if `current_time - vault.last_check_in < min_check_in_cooldown_seconds`
- Return `ContractError::CheckInTooFrequent`
- Add tests for cooldown boundary

---

### 14. Record TTL Extension Amount in Check-In Event
**Labels:** `enhancement`, `ttl`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
The `CHECK_IN_TOPIC` event does not include how many ledgers the TTL was extended by. Off-chain monitors cannot reconstruct the expected expiry without fetching vault storage.

**Tasks:**
- Update `check_in` event payload to include `ttl_extended_ledgers: u32`
- Add a test asserting the emitted value matches `vault_ttl_ledgers(interval)`

---

### 15. Fix: `exit_hibernation` Does Not Re-Extend Vault TTL
**Labels:** `bug`, `ttl`, `hibernation`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
When a vault exits hibernation, the vault's persistent entry TTL is not re-extended. If the vault was near expiry when it entered hibernation, it may expire immediately on exit.

**Tasks:**
- After clearing the `HibernationEntry` in `exit_hibernation`, call the TTL extension helper
- Extend by `vault_ttl_ledgers(vault.check_in_interval)` ledgers
- Add a test: enter hibernation with low TTL, exit, confirm vault is not expired

---

### 16. Add `get_streak_summary` Function
**Labels:** `enhancement`, `ttl`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
`CheckInStreak` tracks the current streak but callers cannot retrieve it without reading raw storage. A typed query function makes this accessible via the contract interface.

**Tasks:**
- Implement `get_streak_summary(env, vault_id) -> Option<CheckInStreak>`
- Return `None` if no streak record exists
- Add tests for zero, active, and broken streaks

---

## Smart Contract — Passkey & Auth

### 17. Enforce Maximum Number of Passkeys Per Vault
**Labels:** `enhancement`, `passkey`, `security`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
There is no cap on the number of passkeys that can be added to a vault. An attacker who gains temporary access could register hundreds of passkeys, making revocation impractical.

**Tasks:**
- Add `max_passkeys_per_vault: u32` to `ProtocolConfig` (default 10)
- Reject `add_passkey` when the count would exceed the cap
- Return `ContractError::PasskeyLimitReached`
- Add tests for limit enforcement

---

### 18. Add `list_passkeys` Function
**Labels:** `enhancement`, `passkey`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Vault owners cannot enumerate all registered passkeys via the contract interface. They must reconstruct the list from event history, which is fragile.

**Tasks:**
- Implement `list_passkeys(env, vault_id) -> Vec<PasskeyHash>`
- Return all currently active (non-revoked) passkeys
- Add tests for empty, single, and multi-passkey vaults

---

### 19. Reject `add_passkey` with Duplicate Hash
**Labels:** `bug`, `passkey`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
Adding the same passkey hash twice does not error. The second add silently overwrites the first entry, resetting its registration timestamp and disrupting audit history.

**Tasks:**
- Check for existing passkey before inserting in `add_passkey`
- Return `ContractError::PasskeyAlreadyRegistered`
- Add a test for the duplicate case

---

### 20. Implement Passkey Last-Used Timestamp Tracking
**Labels:** `enhancement`, `passkey`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
`PasskeyUsageEntry` records usage events but there is no queryable `last_used_at` per passkey. Owners cannot quickly identify stale passkeys without scanning the full usage log.

**Tasks:**
- Add `last_used_at: u64` field to the passkey storage struct
- Update it on every authenticated action
- Implement `get_passkey_last_used(env, vault_id, passkey_hash) -> Option<u64>`
- Add tests for first use and subsequent updates

---

## Smart Contract — Beneficiary & Release

### 21. Add `get_beneficiary_count` Function
**Labels:** `enhancement`, `beneficiary`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
Callers must fetch the full `Vec<BeneficiaryEntry>` to count beneficiaries. A count-only query is cheaper and avoids deserializing all entries.

**Tasks:**
- Implement `get_beneficiary_count(env, vault_id) -> u32`
- Return `0` if no multi-beneficiary list is set
- Add tests for 0, 1, and N beneficiaries

---

### 22. Validate Total BPS Equals 10000 on Each `set_beneficiaries` Call
**Labels:** `bug`, `beneficiary`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
`set_beneficiaries` does not re-validate that BPS sum equals 10000 when called a second time on an existing vault, allowing BPS drift if the function is called with a partial list.

**Tasks:**
- Always recompute BPS sum in `set_beneficiaries` regardless of whether a prior list exists
- Return `ContractError::InvalidBps` when sum != 10000
- Add a test that calls `set_beneficiaries` twice and verifies the second call is also validated

---

### 23. Add Grace Period for Expired-But-Unclaimed Release
**Labels:** `enhancement`, `beneficiary`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
After TTL expiry, `trigger_release` can be called immediately. There is no minimum wait period giving the owner a last chance to check in before funds are transferred.

**Tasks:**
- Add `release_grace_period_seconds: u64` to `ProtocolConfig` (default 0, opt-in)
- In `trigger_release`, require `current_time >= expiry_time + release_grace_period_seconds`
- Return `ContractError::GracePeriodActive` during the grace window
- Add tests for grace period active and expired

---

### 24. Implement `get_release_conditions` Query
**Labels:** `enhancement`, `beneficiary`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
There is no typed function to query all release conditions attached to a vault. Integrations must read raw `DataKey::ReleaseConditions` storage directly.

**Tasks:**
- Implement `get_release_conditions(env, vault_id) -> Vec<ReleaseCondition>`
- Return empty vec if no conditions are set
- Add tests for vaults with zero, one, and multiple conditions

---

### 25. Prevent `trigger_release` When Vault Is Paused
**Labels:** `bug`, `beneficiary`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
The vault-level pause flag (`PAUSE_VAULT_TOPIC`) is respected for owner actions but `trigger_release` does not check for the vault-level pause, only the global contract pause.

**Tasks:**
- Add vault-level pause check at the start of `trigger_release`
- Return `ContractError::VaultPaused`
- Add a test: pause a vault, expire TTL, assert `trigger_release` returns `VaultPaused`

---

### 26. Add `set_release_memo` for On-Chain Inheritance Notes
**Labels:** `enhancement`, `beneficiary`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
Vault owners have no way to attach a final message to the vault that is emitted when funds are released. This is valuable for human-readable inheritance context.

**Tasks:**
- Add `DataKey::ReleaseMemo(u64)` storing up to 256-byte `Bytes`
- Implement `set_release_memo(env, vault_id, caller, memo)`  — owner-only
- Include memo bytes in the `RELEASE_TOPIC` event payload
- Add tests for set, update, and nil memo

---

### 27. Fix: `partial_release` Does Not Verify Caller Is Owner
**Labels:** `bug`, `beneficiary`, `security`
**Priority:** Critical
**Estimated Time:** 30 minutes

**Description:**
`partial_release` is intended to be owner-only, but the authorization check uses `vault.require_auth()` which may not correctly bind to the vault owner field in all execution paths.

**Tasks:**
- Audit `partial_release` auth check against `vault.owner`
- Replace with explicit `vault.owner.require_auth()` if not already present
- Add a test where a non-owner caller is rejected

---

### 28. Emit Event When Beneficiary Conflict Auto-Expires
**Labels:** `enhancement`, `beneficiary`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
Beneficiary conflicts have a resolution timeout, but when the timeout passes without resolution, no on-chain event is emitted. The conflict silently becomes stale.

**Tasks:**
- Add `CONFLICT_EXPIRED_TOPIC: Symbol = symbol_short!("conf_exp")`
- Emit it in `resolve_conflict` or a new `expire_conflict` function when called after timeout with no resolution
- Add tests for pre- and post-timeout expiry

---

### 29. Validate Beneficiary Address Is Not Zero Address
**Labels:** `bug`, `beneficiary`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
Neither `set_beneficiaries` nor `update_beneficiary` checks whether a beneficiary address is the zero/null address. Setting a null beneficiary would irrecoverably burn released funds.

**Tasks:**
- Add a helper `assert_not_zero_address(addr)` in the contract
- Call it for every beneficiary address in `set_beneficiaries` and `update_beneficiary`
- Return `ContractError::InvalidAddress`
- Add tests for zero-address rejection

---

### 30. Add `get_unconditional_release_time` Function
**Labels:** `enhancement`, `beneficiary`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Given vault creation time and check-in interval, the earliest possible release time (if no further check-ins occur) can be computed. Beneficiaries need this for planning.

**Tasks:**
- Implement `get_unconditional_release_time(env, vault_id) -> u64`
- Return `vault.last_check_in + vault.check_in_interval`
- Return `0` if the vault is already expired/released
- Add tests for active, near-expiry, and released vaults

---

## Smart Contract — Multi-Sig

### 31. Add `list_open_proposals` for a Vault
**Labels:** `enhancement`, `multi-sig`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Signers cannot enumerate which proposals are currently open without knowing proposal IDs. There is no index of pending proposals per vault.

**Tasks:**
- Add `DataKey::OpenProposals(u64)` storing `Vec<u64>` (proposal IDs) per vault
- Update it on `propose`, `execute`, and rejection
- Implement `list_open_proposals(env, vault_id) -> Vec<u64>`
- Add tests for creation, execution removal, and empty state

---

### 32. Enforce Minimum Signers Threshold Is at Least 1
**Labels:** `bug`, `multi-sig`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
`configure_multisig` does not validate that `required_approvals >= 1`. A threshold of 0 would allow any proposal to be executed with no approvals.

**Tasks:**
- Add guard: `required_approvals >= 1 && required_approvals <= signers.len()`
- Return `ContractError::InvalidMultisigConfig`
- Add tests for `required_approvals = 0` and `required_approvals > signers.len()`

---

### 33. Implement Multi-Sig Proposal Veto by Single Signer
**Labels:** `enhancement`, `multi-sig`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
Once a proposal reaches the required approval count it executes. There is no way for a dissenting signer to block execution even if they detect fraud.

**Tasks:**
- Add `veto_proposal(env, vault_id, proposal_id, caller)` — any registered signer
- A vetoed proposal is immediately cancelled with `ProposalStatus::Vetoed`
- Emit `MULTISIG_VETOED_TOPIC`
- Add tests for veto before and after threshold is reached

---

### 34. Add Multi-Sig Signer Removal Without Full Reconfiguration
**Labels:** `enhancement`, `multi-sig`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Removing a single compromised signer requires calling `configure_multisig` with the full new signer list. This is error-prone and does not cancel proposals the removed signer already approved.

**Tasks:**
- Implement `remove_multisig_signer(env, vault_id, caller, signer_to_remove)`
- Automatically cancel any open proposals that would no longer reach threshold
- Emit `MULTISIG_SIGNER_REMOVED_TOPIC`
- Add tests for removal, threshold downgrade, and proposal cancellation

---

### 35. Require Multi-Sig Approval for Vault Cancellation When Multi-Sig Is Active
**Labels:** `enhancement`, `multi-sig`, `security`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
`cancel_vault` only requires the owner's signature. If a vault has multi-sig configured, cancellation should also require the multi-sig threshold to prevent a compromised owner key from unilaterally destroying the vault.

**Tasks:**
- In `cancel_vault`, check if a `MultiSigConfig` exists for the vault
- If yes, require cancellation to be submitted as a multi-sig proposal
- Add tests for single-owner cancel (no multi-sig) and multi-sig-required cancel

---

## Smart Contract — Vesting

### 36. Add `get_total_unvested_amount` Function
**Labels:** `enhancement`, `vesting`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
There is no function to query the total amount still locked in vesting schedules for a vault. Beneficiaries cannot determine how much remains unvested without reading all schedules.

**Tasks:**
- Implement `get_total_unvested_amount(env, vault_id) -> i128`
- Sum `amount - claimed` across all active vesting schedules
- Add tests for zero, partial, and fully vested states

---

### 37. Enforce Vesting Schedule End Date Is After Start Date
**Labels:** `bug`, `vesting`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
`set_vesting_schedule` does not validate that `end_time > start_time`. A malformed schedule with equal or reversed times causes division-by-zero or incorrect linear interpolation.

**Tasks:**
- Add `assert(schedule.end_time > schedule.start_time)` in schedule creation
- Return `ContractError::InvalidVestingSchedule`
- Add tests for equal timestamps and reversed timestamps

---

### 38. Add `cancel_vesting_schedule` for Owner
**Labels:** `enhancement`, `vesting`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Once set, a vesting schedule cannot be cancelled. If the beneficiary relationship changes, the owner is stuck with schedules that release to the wrong address.

**Tasks:**
- Implement `cancel_vesting_schedule(env, vault_id, schedule_id, caller)` — owner-only
- Return unclaimed vested amounts to the vault balance
- Emit `VESTING_CANCELLED_TOPIC`
- Add tests for cancel before and after partial claims

---

### 39. Fix: `claim_vested` Does Not Check Vault Is Not Cancelled
**Labels:** `bug`, `vesting`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
`claim_vested` checks for vault expiry but not for `Cancelled` status. A beneficiary could claim vesting from a cancelled vault that should have zero accessible funds.

**Tasks:**
- Add cancelled status guard at the start of `claim_vested`
- Return `ContractError::VaultCancelled`
- Add a test confirming the rejection

---

### 40. Add `get_vesting_schedule_count` Per Vault
**Labels:** `enhancement`, `vesting`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
Callers must read all schedules to know how many exist. Given the `MAX_VESTING_SCHEDULES` cap, a count query avoids unnecessary deserialization.

**Tasks:**
- Implement `get_vesting_schedule_count(env, vault_id) -> u32`
- Add tests for 0, 1, and max schedules

---

## Smart Contract — Ownership Transfer

### 41. Add `cancel_ownership_transfer` by New Owner
**Labels:** `enhancement`, `ownership`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
`cancel_ownership_transfer` can only be called by the current owner. The pending new owner has no way to decline the transfer if they do not want the vault.

**Tasks:**
- Allow the pending `new_owner` to also call `cancel_ownership_transfer`
- Emit `OWNERSHIP_CANCELLED_TOPIC` with a `reason: "declined"` field
- Add tests for declination by new owner and rejection by an unrelated address

---

### 42. Emit Event When Ownership Transfer Timelock Expires Without Acceptance
**Labels:** `enhancement`, `ownership`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
An ownership transfer request expires after `OWNERSHIP_TRANSFER_EXPIRY` (7 days) with no on-chain signal. Indexers must poll storage to detect expired requests.

**Tasks:**
- Add `OWNERSHIP_TRANSFER_EXPIRED_TOPIC: Symbol = symbol_short!("own_exp")`
- Implement `expire_ownership_transfer(env, vault_id)` — callable by anyone after expiry
- Emit the event and clean up the pending request
- Add tests for pre-expiry rejection and post-expiry success

---

### 43. Prevent Ownership Transfer to Current Owner
**Labels:** `bug`, `ownership`
**Priority:** Low
**Estimated Time:** 15 minutes

**Description:**
`initiate_ownership_transfer` does not check whether `new_owner == vault.owner`. A no-op transfer wastes gas and creates a spurious event.

**Tasks:**
- Add `require(new_owner != vault.owner)` check
- Return `ContractError::AlreadyOwner`
- Add a test asserting the error

---

## Smart Contract — Admin & Protocol

### 44. Implement Two-Step Protocol Configuration Update
**Labels:** `enhancement`, `admin`, `security`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
`set_protocol_config` (or equivalent) applies changes immediately. A misconfigured value (e.g., `max_check_in_interval = 0`) takes effect instantly and can brick all vaults.

**Tasks:**
- Add `propose_protocol_config(env, config)` — admin-only, stores pending config
- Add `apply_protocol_config(env)` — callable after a 24-hour timelock
- Emit `PROTOCOL_CONFIG_PROPOSED_TOPIC` and `PROTOCOL_CONFIG_APPLIED_TOPIC`
- Add tests for timelock enforcement and immediate application rejection

---

### 45. Add `get_protocol_config` Query Function
**Labels:** `enhancement`, `admin`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
Off-chain clients cannot retrieve the current protocol configuration without reading raw storage keys. A typed query prevents key-name coupling.

**Tasks:**
- Implement `get_protocol_config(env) -> ProtocolConfig`
- Add tests confirming the returned struct matches what was set

---

### 46. Enforce Admin Address Cannot Be a Vault Owner
**Labels:** `enhancement`, `admin`, `security`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
The admin address has privileged operations (pause, upgrade, dispute resolution). If the admin is also a vault owner, they could manipulate their own vault's release.

**Tasks:**
- In `create_vault`, reject if `caller == admin`
- In `initialize`, document and optionally enforce this invariant
- Return `ContractError::AdminCannotOwnVault`
- Add tests for the rejection

---

### 47. Add `get_admin` Query Function
**Labels:** `enhancement`, `admin`
**Priority:** Low
**Estimated Time:** 15 minutes

**Description:**
There is no public function to retrieve the current admin address. Clients must read raw storage, which is brittle.

**Tasks:**
- Implement `get_admin(env) -> Address`
- Add a test asserting it returns the initialized admin

---

### 48. Implement Admin Transfer with Timelock
**Labels:** `enhancement`, `admin`, `security`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
There is no mechanism to transfer the admin role. If the admin key is compromised, there is no recovery path and no way to upgrade the admin.

**Tasks:**
- Add `propose_new_admin(env, new_admin)` — current admin only
- Add `accept_admin(env)` — new admin only, callable after 24-hour timelock
- Emit `ADMIN_TRANSFER_PROPOSED_TOPIC` and `ADMIN_TRANSFER_COMPLETED_TOPIC`
- Add tests for full transfer flow and timelock enforcement

---

### 49. Add Contract Pause Reason Tracking
**Labels:** `enhancement`, `admin`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
`pause_contract` sets the paused flag but does not record why or who paused it. Operators and auditors must examine logs externally.

**Tasks:**
- Store `PauseRecord { paused_by: Address, reason: Bytes, paused_at: u64 }` on pause
- Include in the `PAUSE_TOPIC` event
- Implement `get_pause_record(env) -> Option<PauseRecord>`
- Add tests for pause with reason and cleared record on unpause

---

### 50. Validate `initialize` Cannot Be Called with Expired-Looking Timestamps
**Labels:** `bug`, `admin`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
`initialize` sets contract-level state but does not validate that the provided timestamps or config values are consistent with the current ledger time. A misconfigured initialization can create permanently broken state.

**Tasks:**
- Assert `min_check_in_interval > 0` and `max_check_in_interval >= min_check_in_interval`
- Return `ContractError::InvalidConfig`
- Add tests for zero interval and inverted min/max

---

## Smart Contract — ZK Verifier

### 51. Replace ZK Verifier Stub with Groth16 Verification Logic
**Labels:** `enhancement`, `zk-verifier`, `security`
**Priority:** High
**Estimated Time:** 8 hours

**Description:**
`ZkVerifierContract::verify_claim` is an explicit stub that only checks for non-empty bytes. Any non-empty proof passes, making the ZK layer security-theater.

**Tasks:**
- Research available Soroban host cryptographic primitives (BLS12-381, SHA-256, etc.)
- Implement or integrate a Groth16 or PLONK verifier using available host functions
- If full on-chain ZK is not yet feasible, implement a trusted-oracle verification model with clear documentation of the trust assumptions
- Remove the 0x00 sentinel and non-empty guard as the sole security mechanism
- Add tests with known valid and invalid proofs

---

### 52. Add `verify_claim` Input Size Limits
**Labels:** `bug`, `zk-verifier`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
`verify_claim` accepts unbounded `proof` and `claim` byte arrays. A very large input could exhaust the instruction budget and cause other legitimate calls to fail.

**Tasks:**
- Add `MAX_PROOF_SIZE: u32 = 4096` and `MAX_CLAIM_SIZE: u32 = 1024` constants
- Reject inputs exceeding these limits with `VerifierError::ProofTooLarge` / `VerifierError::ClaimTooLarge`
- Add tests for boundary values

---

### 53. Emit an Event from `verify_claim` for Audit Purposes
**Labels:** `enhancement`, `zk-verifier`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
`verify_claim` returns a boolean but emits no event. Off-chain monitors cannot detect verification failures or correlate them to specific vaults.

**Tasks:**
- Emit a `VERIFY_CLAIM_TOPIC` event with `result: bool` and `claim_hash: BytesN<32>`
- Add tests asserting the event is emitted for both `true` and `false` results

---

## Backend — API & Handlers

### 54. Add Request Body Size Limit Middleware
**Labels:** `enhancement`, `backend`, `security`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
The backend HTTP server has no per-request body size limit. An attacker can send a multi-GB request body and exhaust server memory.

**Tasks:**
- Add a `ContentLengthLimit` middleware (e.g., Axum's `DefaultBodyLimit::max(1_048_576)` — 1 MB)
- Return HTTP 413 for oversized bodies
- Add tests for oversized and normal-sized payloads

---

### 55. Implement Structured Error Responses Across All Handlers
**Labels:** `enhancement`, `backend`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
Error responses from different handlers have inconsistent JSON shapes. Some return `{ "error": "..." }`, others return plain strings or HTML. Clients cannot reliably parse errors.

**Tasks:**
- Define a unified `ApiError { code: String, message: String, details: Option<Value> }` struct
- Implement `IntoResponse` for it
- Replace all ad-hoc error returns in `handlers.rs` with `ApiError`
- Add tests for each error variant's JSON shape

---

### 56. Add Health Check Endpoint
**Labels:** `enhancement`, `backend`, `infrastructure`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
There is no `/health` or `/ready` endpoint. Load balancers and orchestrators (Kubernetes, ECS) cannot determine if the backend is healthy.

**Tasks:**
- Add `GET /health` returning `{ "status": "ok", "version": "..." }` with HTTP 200
- Add `GET /ready` that also checks database connectivity
- Add tests for both endpoints

---

### 57. Implement Database Connection Pool Size Configuration
**Labels:** `enhancement`, `backend`, `infrastructure`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
The database connection pool size is hardcoded. Under high load, the pool exhausts and requests queue indefinitely. Under low load, it holds unnecessary connections.

**Tasks:**
- Add `DB_POOL_MIN`, `DB_POOL_MAX`, and `DB_POOL_TIMEOUT_SECS` to `.env.example`
- Read them in the pool initialization code in `db.rs`
- Add defaults (min=2, max=10, timeout=30)
- Document in `.env.example`

---

### 58. Add CORS Configuration to Backend
**Labels:** `enhancement`, `backend`, `security`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
The backend has no CORS middleware. Browser-based frontends on different origins cannot call the API, and wildcard CORS is a security risk.

**Tasks:**
- Add `tower-http` CORS layer with configurable `ALLOWED_ORIGINS` env var
- Default to denying all origins if not configured
- Add tests for allowed and rejected origins

---

### 59. Fix: `scheduler.rs` Does Not Handle Database Errors Gracefully
**Labels:** `bug`, `backend`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
The reminder scheduler loop in `scheduler.rs` calls database functions but does not handle `Err` variants. A transient DB error causes the scheduler task to silently terminate.

**Tasks:**
- Wrap all DB calls in the scheduler loop with `match` or `?` with error logging
- On error, log the error and continue to the next iteration (do not crash)
- Add tests for scheduler resilience with a mock DB that returns errors

---

### 60. Add Idempotency Key Support for Reminder Creation
**Labels:** `enhancement`, `backend`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
The reminder creation endpoint has no idempotency key support. Retried requests create duplicate reminders, leading to duplicate notification delivery.

**Tasks:**
- Accept `Idempotency-Key` header on POST endpoints
- Store processed keys in the database with a 24-hour TTL
- Return the cached response for duplicate keys
- Add tests for idempotent and non-idempotent requests

---

## Backend — Notifications & Reminders

### 61. Add Notification Deduplication Window
**Labels:** `enhancement`, `backend`, `notifications`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
If the scheduler fires twice in quick succession (restart, clock skew), the same reminder can be delivered twice. Recipients receive duplicate emails/SMS.

**Tasks:**
- Add `sent_at: Option<DateTime>` to the reminder record
- Before sending, check if a reminder was sent within the last `DEDUP_WINDOW_SECONDS` (default 300)
- Skip and log if within the window
- Add tests for deduplication and edge of window

---

### 62. Implement Notification Channel Priority Fallback
**Labels:** `enhancement`, `backend`, `notifications`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
If email delivery fails, there is no automatic fallback to SMS (or vice versa). Vault owners miss reminders when their primary channel is unavailable.

**Tasks:**
- Add `preferred_channel: NotificationChannel` and `fallback_channel: Option<NotificationChannel>` to user preferences
- On primary channel failure, retry via fallback channel after 5 minutes
- Emit delivery logs for both attempts
- Add tests for fallback trigger and suppression when no fallback is configured

---

### 63. Add Unsubscribe Link in Reminder Emails
**Labels:** `enhancement`, `backend`, `notifications`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
Reminder emails do not include an unsubscribe link. This violates CAN-SPAM / GDPR requirements and may cause spam filter classification.

**Tasks:**
- Generate a signed unsubscribe token per email recipient
- Add `GET /notifications/unsubscribe?token=<signed_token>` endpoint
- Include the URL in email templates in `templates.rs`
- Mark the user as unsubscribed in the database
- Add tests for token generation, validation, and unsubscribe effect

---

### 64. Implement Notification Retry Budget
**Labels:** `enhancement`, `backend`, `notifications`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
The retry logic in `notifications.rs` retries indefinitely (or up to a very large count). A consistently-failing address will consume API quota forever.

**Tasks:**
- Add `max_retry_attempts: u32` (default 5) per notification record
- After exhausting retries, mark the notification as `Failed` and stop retrying
- Emit a log warning and optionally alert the admin
- Add tests for retry exhaustion

---

### 65. Add Email Template Internationalization Support
**Labels:** `enhancement`, `backend`, `notifications`
**Priority:** Low
**Estimated Time:** 3 hours

**Description:**
All email templates in `templates.rs` are English-only. Users who set a non-English locale receive English notifications, reducing engagement and clarity.

**Tasks:**
- Add `locale: Option<String>` to the user/vault notification preferences
- Add template variants for at least `en`, `es`, `fr`, `de` in `templates.rs`
- Fall back to `en` if the locale is unsupported
- Add tests for locale selection and fallback

---

## Backend — WebSocket

### 66. Add WebSocket Heartbeat / Ping-Pong
**Labels:** `bug`, `backend`, `websocket`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
The WebSocket server in `websocket.rs` has no heartbeat. Idle connections from clients behind NAT or proxies are silently dropped, causing clients to believe they are connected when they are not.

**Tasks:**
- Send a `ping` frame every 30 seconds per connection
- Close connections that do not respond within 10 seconds
- Add tests for connection cleanup on missed pong

---

### 67. Implement WebSocket Authentication
**Labels:** `enhancement`, `backend`, `websocket`, `security`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
The WebSocket endpoint in `websocket.rs` has no authentication. Any client can connect and receive vault status events for any vault ID.

**Tasks:**
- Require a signed JWT token in the WebSocket upgrade request (`Authorization` header or query param)
- Validate the token and extract the authenticated user's vault IDs
- Only push events for vaults the user owns or is a beneficiary of
- Add tests for unauthenticated rejection and authorized event scoping

---

### 68. Add WebSocket Message Rate Limiting
**Labels:** `enhancement`, `backend`, `websocket`, `security`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
A WebSocket client can flood the server with inbound messages. There is no per-connection rate limit, enabling DoS via message spam.

**Tasks:**
- Implement per-connection inbound message rate limit (default 10 msg/sec)
- Close the connection with a `1008 Policy Violation` close code on limit exceeded
- Add tests for rate limit trigger and normal message handling

---

## Backend — Database

### 69. Add Database Migration Version Tracking Table
**Labels:** `enhancement`, `backend`, `infrastructure`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
The database schema in `db.rs` is applied without version tracking. Restarting the service on a partially-migrated database can cause silent data corruption.

**Tasks:**
- Add a `schema_migrations` table tracking applied migration versions
- Run each migration only if its version is not already in the table
- Log migration events on startup
- Add tests for fresh install and already-migrated state

---

### 70. Implement Soft Delete for Vault Reminder Records
**Labels:** `enhancement`, `backend`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
Reminder records are hard-deleted when a vault is cancelled. Audit queries cannot determine whether reminders were sent for cancelled vaults.

**Tasks:**
- Add `deleted_at: Option<DateTime>` to the reminder table
- Replace hard deletes with soft deletes
- Exclude soft-deleted records from active queries
- Add `GET /vaults/{id}/reminders?include_deleted=true` for admin audit
- Add tests for soft delete and exclusion

---

## Mobile — Android

### 71. Implement Biometric Prompt Before Check-In on Android
**Labels:** `enhancement`, `mobile`, `android`, `security`
**Priority:** High
**Estimated Time:** 3 hours

**Description:**
The Android app performs vault check-in without requiring biometric confirmation. A stolen unlocked device can perform check-ins silently.

**Tasks:**
- Integrate `BiometricPrompt` API before triggering check-in
- Fall back to device PIN if biometric is not available
- Show a confirmation dialog with vault name and expected TTL extension
- Add instrumented tests for biometric prompt lifecycle

---

### 72. Add Offline Check-In Queuing for Android
**Labels:** `enhancement`, `mobile`, `android`
**Priority:** Medium
**Estimated Time:** 4 hours

**Description:**
Check-ins fail silently when the device is offline. Users who check in while in airplane mode are unaware the check-in was not submitted, and the vault TTL may lapse.

**Tasks:**
- Queue pending check-ins in a local Room database when offline
- Retry queued check-ins when connectivity is restored using `WorkManager`
- Show a persistent notification while a check-in is queued
- Add unit tests for queue persistence and flush

---

### 73. Implement Deep Link Handling for Beneficiary Acceptance on Android
**Labels:** `enhancement`, `mobile`, `android`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
Beneficiary acceptance links sent via email open the browser, not the app. There is no Android deep link / App Link handler for the acceptance flow.

**Tasks:**
- Add `intent-filter` with `https://ttl-legacy.app/accept?vault_id=...` in `AndroidManifest.xml`
- Handle the intent in the acceptance activity and pre-populate the vault ID
- Verify the App Link with a `.well-known/assetlinks.json` entry
- Add tests for intent resolution

---

### 74. Add Push Notification Permission Request Flow on Android
**Labels:** `enhancement`, `mobile`, `android`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
On Android 13+, notification permission must be requested at runtime. The app does not request this permission, so push notifications are silently dropped.

**Tasks:**
- Request `POST_NOTIFICATIONS` permission on first launch (Android 13+)
- Show an educational rationale dialog before the system prompt
- Handle denial gracefully and allow re-request from settings
- Add instrumented tests for permission flow

---

### 75. Implement Vault Status Widget for Android Home Screen
**Labels:** `enhancement`, `mobile`, `android`
**Priority:** Low
**Estimated Time:** 4 hours

**Description:**
There is no Android home screen widget showing vault TTL remaining and check-in status. Users must open the app to check their vault health.

**Tasks:**
- Implement an `AppWidget` showing vault name, TTL remaining, and last check-in time
- Update the widget on a periodic `WorkManager` task (every 15 minutes)
- Tap on the widget opens the check-in screen
- Add instrumented tests for widget update and tap handling

---

## Mobile — iOS

### 76. Add Face ID / Touch ID Authentication Before Check-In on iOS
**Labels:** `enhancement`, `mobile`, `ios`, `security`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
The iOS app performs vault check-in without biometric confirmation. A borrowed unlocked device can perform check-ins silently.

**Tasks:**
- Use `LocalAuthentication` framework to require Face ID or Touch ID before `VaultCheckInService.checkIn()`
- Fall back to passcode if biometry is unavailable
- Add UI tests for biometric success and fallback flows

---

### 77. Implement iOS Lock Screen Widget (WidgetKit)
**Labels:** `enhancement`, `mobile`, `ios`
**Priority:** Low
**Estimated Time:** 4 hours

**Description:**
There is no iOS lock screen or home screen widget for TTL status. Users must open the app to check urgency.

**Tasks:**
- Add a WidgetKit `Widget` extension showing vault name and TTL countdown
- Refresh on a `TimelineProvider` that reloads every 15 minutes
- Handle multiple vaults by showing the one with the lowest TTL remaining
- Add snapshot and timeline tests

---

### 78. Add Universal Link Handling for Vault Invitations on iOS
**Labels:** `enhancement`, `mobile`, `ios`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
Vault invitation and beneficiary acceptance links do not open the iOS app. Users are redirected to the browser.

**Tasks:**
- Add Associated Domains entitlement (`applinks:ttl-legacy.app`)
- Implement `scene(_:continue:)` to handle incoming `NSUserActivity` for vault links
- Route the user to the correct screen based on the path and parameters
- Add tests for link routing

---

### 79. Implement Background Refresh for TTL Monitoring on iOS
**Labels:** `enhancement`, `mobile`, `ios`
**Priority:** High
**Estimated Time:** 3 hours

**Description:**
The iOS app only updates vault TTL when opened. If the TTL lapses while the app is in the background, the user receives no warning.

**Tasks:**
- Register a `BGAppRefreshTask` to poll vault TTL every hour
- Send a local `UNUserNotificationCenter` notification if TTL < 24 hours
- Request `BGAppRefreshTask` permission and handle scheduling
- Add tests for background task registration and notification scheduling

---

### 80. Add iCloud Keychain Backup Option for Passkey Metadata on iOS
**Labels:** `enhancement`, `mobile`, `ios`, `security`
**Priority:** Medium
**Estimated Time:** 3 hours

**Description:**
Passkey metadata (not the private key, but vault association data) is stored only in the local app sandbox. A device restore loses all vault associations.

**Tasks:**
- Identify which passkey metadata is safe to back up (no private keys)
- Sync vault-to-passkey association data via `NSUbiquitousKeyValueStore` or CloudKit
- Add a user toggle: "Sync vault associations to iCloud" in settings
- Add tests for sync, restore, and toggle behavior

---

## Testing & Quality

### 81. Add Fuzz Testing for Vesting Schedule Calculation
**Labels:** `testing`, `security`
**Priority:** High
**Estimated Time:** 3 hours

**Description:**
Linear vesting interpolation involves integer arithmetic that can overflow or produce incorrect results for extreme timestamps or amounts. Fuzz tests would catch these edge cases.

**Tasks:**
- Set up `cargo-fuzz` target for the vesting module
- Fuzz `compute_vested_amount(schedule, current_time)` with random schedules and timestamps
- Assert that result is always in `[0, schedule.total_amount]`
- Run for 30 minutes and document findings

---

### 82. Add Invariant Tests for BPS Sum After Multi-Beneficiary Operations
**Labels:** `testing`, `quality`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
After any sequence of `set_beneficiaries`, beneficiary caps, floors, and ranking operations, the sum of allocated BPS must remain 10000. There are no invariant tests for this property.

**Tasks:**
- Add `#[test] fn bps_sum_invariant_after_set_beneficiaries()`
- Add `#[test] fn bps_sum_invariant_after_cap_application()`
- Use `proptest` to generate random BPS splits and verify the invariant holds
- Document the invariant in `docs/beneficiary-advanced-features.md`

---

### 83. Add Integration Test: Full Vault Lifecycle on Local Soroban
**Labels:** `testing`, `quality`
**Priority:** High
**Estimated Time:** 3 hours

**Description:**
The existing integration tests in `contracts/ttl_vault/tests/integration_tests.rs` do not cover the full lifecycle: create → deposit → multi-check-in → TTL expiry → trigger_release → verify beneficiary balance.

**Tasks:**
- Add `test_full_lifecycle_single_beneficiary()` in `integration_tests.rs`
- Add `test_full_lifecycle_multi_beneficiary_bps_split()`
- Add `test_full_lifecycle_with_hibernation()`
- Assert exact token balances at each step

---

### 84. Add Property-Based Tests for TTL Extension Calculation
**Labels:** `testing`, `quality`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
`vault_ttl_ledgers(interval)` must be monotonically non-decreasing with `interval` and must never exceed `MAX_PERSISTENT_TTL`. There are no property tests for this.

**Tasks:**
- Add `proptest` tests for `vault_ttl_ledgers` with random intervals
- Assert: `result <= MAX_PERSISTENT_TTL`
- Assert: `vault_ttl_ledgers(a) >= vault_ttl_ledgers(b)` when `a >= b`
- Run on every CI build

---

### 85. Add Negative Tests for All `ContractError` Variants
**Labels:** `testing`, `quality`
**Priority:** Medium
**Estimated Time:** 3 hours

**Description:**
`ContractError` has dozens of variants but many have no corresponding negative test asserting they are actually returned in the right scenario.

**Tasks:**
- Enumerate all `ContractError` variants in `lib.rs`
- For each variant without a test, add one in `test.rs` triggering that specific error
- Ensure CI fails if any variant is untested
- Add a comment in each test linking to the contract function

---

### 86. Add Tests for Backend `notifications.rs` Email and SMS Delivery
**Labels:** `testing`, `backend`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
`notifications.rs` calls external email/SMS APIs but has no tests with mocked HTTP clients. A regression in notification logic would only be caught in production.

**Tasks:**
- Add `mockito` or `wiremock` as a dev dependency
- Add tests for: successful email send, failed email with retry, successful SMS, rate-limited SMS
- Assert that the correct payload is sent to the external API

---

### 87. Add Load Test for `trigger_release` with 50-Beneficiary Vault
**Labels:** `testing`, `performance`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
`trigger_release` iterates over all beneficiaries and issues token transfers. For a vault with 50 beneficiaries, this may exceed Soroban's instruction budget.

**Tasks:**
- Add a test with a vault configured with 50 beneficiaries at equal BPS
- Measure instruction consumption
- If it exceeds 80% of the limit, implement a paginated release mechanism
- Document the maximum safe beneficiary count

---

### 88. Add Regression Test for Vault ID Uniqueness Under Concurrent Creation
**Labels:** `testing`, `bug`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
Vault ID assignment uses a counter. If two `create_vault` calls land in the same ledger transaction sequence, ID uniqueness must still hold. There is no regression test for this.

**Tasks:**
- Add `test_vault_ids_are_unique_across_multiple_creates()` in `test.rs`
- Create 100 vaults in sequence and assert all IDs are distinct
- Add `test_vault_id_counter_is_consistent_after_failure()` — simulate a failed create and verify the counter did not advance

---

## Documentation

### 89. Add `docs/zk-verifier.md` Explaining the Stub and Migration Path
**Labels:** `documentation`, `zk-verifier`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
The `zk_verifier` contract is a stub, but there is no documentation explaining what it is, why it is a stub, and what the migration path to a real ZK implementation looks like.

**Tasks:**
- Create `docs/zk-verifier.md`
- Document the current stub behavior and its security limitations
- Document what a real ZK implementation requires (Groth16, host functions, trusted setup)
- Add a roadmap entry for full ZK implementation

---

### 90. Add `docs/multi-sig.md` Update with Veto and Signer Removal
**Labels:** `documentation`, `multi-sig`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
`docs/multi-sig.md` describes the basic multi-sig flow but does not document the veto right or signer removal function (once implemented).

**Tasks:**
- Update `docs/multi-sig.md` with veto workflow diagram
- Document `remove_multisig_signer` behavior including proposal cancellation
- Add a table of multi-sig error codes and their meanings

---

### 91. Create `docs/backend-api.md` with Full Endpoint Reference
**Labels:** `documentation`, `backend`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
There is no API reference for the backend server. Developers integrating the frontend or mobile apps must read `handlers.rs` source code to discover endpoints.

**Tasks:**
- Document all endpoints in `docs/backend-api.md`: method, path, request body, response body, error codes
- Add request/response examples in JSON
- Cross-reference with `routes.rs` to ensure completeness
- Add a note on authentication requirements per endpoint

---

### 92. Add `docs/mobile-passkey-flow.md` for iOS and Android
**Labels:** `documentation`, `mobile`, `passkey`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
The passkey integration for mobile is undocumented. Developers cannot understand how WebAuthn credentials are created and used across iOS and Android.

**Tasks:**
- Create `docs/mobile-passkey-flow.md`
- Document the credential creation flow on iOS (ASAuthorization) and Android (Credential Manager)
- Document how the passkey public key is registered with the smart contract
- Add sequence diagrams for registration and authentication

---

### 93. Add `docs/token-management.md` Section on Fee Calculation
**Labels:** `documentation`, `token-management`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
`docs/token-management.md` describes token operations but does not explain how swap fees and conversion fees are calculated. Users cannot predict costs.

**Tasks:**
- Add a "Fee Calculation" section to `docs/token-management.md`
- Show the formula for each fee type (swap, conversion, staking)
- Add worked examples with sample values
- Document which fees go to the protocol treasury vs. the vault

---

### 94. Create OpenAPI Specification for Backend
**Labels:** `documentation`, `backend`, `infrastructure`
**Priority:** High
**Estimated Time:** 3 hours

**Description:**
There is no OpenAPI/Swagger specification for the backend. SDKs cannot be auto-generated and API consumers have no machine-readable contract.

**Tasks:**
- Create `docs/openapi.yaml` (OpenAPI 3.1)
- Cover all endpoints from `routes.rs`
- Add request/response schemas matching `models.rs` structs
- Validate the spec against the actual handlers with a test
- Add a CI step that fails if the spec is out of sync with a basic lint

---

## Infrastructure & DevOps

### 95. Add `cargo audit` to CI Pipeline
**Labels:** `infrastructure`, `security`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
The CI workflow runs `cargo test` and `cargo clippy` but not `cargo audit`. Known vulnerabilities in dependencies go undetected.

**Tasks:**
- Add `cargo audit` step to `.github/workflows/ci.yml`
- Configure it to fail on any `CRITICAL` or `HIGH` severity advisory
- Add `.cargo/audit.toml` with any accepted advisories and justification
- Document the audit process in `CONTRIBUTING.md`

---

### 96. Add Dependabot Configuration for Rust and GitHub Actions
**Labels:** `infrastructure`, `security`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
There is no Dependabot configuration. Dependency updates (including security patches) must be applied manually.

**Tasks:**
- Create `.github/dependabot.yml`
- Configure weekly Rust (`cargo`) dependency updates
- Configure weekly GitHub Actions updates
- Set `assignees` and `labels` for dependency PRs

---

### 97. Add Docker Compose Setup for Local Development
**Labels:** `infrastructure`, `developer-experience`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
The backend requires a database but there is no `docker-compose.yml` for local development. Developers must manually set up PostgreSQL.

**Tasks:**
- Create `docker-compose.yml` with `backend`, `db` (PostgreSQL), and `stellar-quickstart` services
- Add `docker-compose.override.yml` for development-specific settings
- Document the setup in `README.md`
- Add a health check for the `db` service

---

### 98. Implement Contract Deployment Idempotency Check in Deploy Scripts
**Labels:** `infrastructure`, `scripts`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Running `deploy_testnet.sh` twice deploys a second contract instance rather than detecting and reusing an existing deployment. This wastes gas and creates configuration drift.

**Tasks:**
- Check for an existing contract address in `environments.toml` before deploying
- Prompt the user to confirm re-deployment if an address already exists
- Write the new address back to `environments.toml` on success
- Add a `--force` flag to skip the check

---

### 99. Add Contract WASM Size Check to CI
**Labels:** `infrastructure`, `performance`
**Priority:** Medium
**Estimated Time:** 30 minutes

**Description:**
Soroban WASM size affects deployment cost and instruction budget. There is no CI gate to detect accidental WASM size regressions.

**Tasks:**
- Add a CI step that builds the contract WASM with `--release`
- Assert the WASM size is below a configured threshold (e.g., 512 KB)
- Print the actual size in the CI log
- Add `docs/wasm-size-budget.md` documenting the budget and optimization strategies

---

### 100. Implement Automated Testnet Smoke Test in CI
**Labels:** `infrastructure`, `testing`
**Priority:** High
**Estimated Time:** 4 hours

**Description:**
CI only runs unit tests locally. There is no automated deployment and smoke test on Stellar testnet, so deployment-time bugs (network fees, contract init, token setup) are found manually.

**Tasks:**
- Add a nightly CI workflow that deploys to testnet using a funded test keypair
- Run a minimal smoke test: create vault, deposit, check-in, get TTL, cancel
- Store the test contract address and clean up after the test
- Alert on failure via a GitHub Actions notification

---

## Security

### 101. Implement Replay Attack Prevention for Check-In Delegation
**Labels:** `security`, `check-in`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
`check_in` delegation allows a delegated address to check in on behalf of the owner. A delegated check-in transaction could be captured and replayed to extend TTL at a later time against the owner's intent.

**Tasks:**
- Add a per-delegation nonce stored in `DataKey::DelegateNonce(vault_id, delegate_address)`
- Require delegates to include the nonce in their check-in call
- Increment the nonce after each successful delegated check-in
- Add tests for replay rejection and nonce increment

---

### 102. Add Rate Limiting for `trigger_release` Calls
**Labels:** `security`, `vault-core`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
`trigger_release` can be called repeatedly by anyone once the vault is expired. Each call reprocesses beneficiary distribution and emits events. This can be abused for event spam.

**Tasks:**
- Add a `DataKey::ReleaseAttempted(vault_id)` flag set after the first successful release
- Reject subsequent calls with `ContractError::AlreadyReleased`
- Verify the flag is set atomically with the token transfer
- Add tests for double-release rejection

---

### 103. Implement Withdrawal Destination Validation Against Vault Owner
**Labels:** `security`, `vault-core`
**Priority:** High
**Estimated Time:** 30 minutes

**Description:**
`withdraw` does not validate that the destination address is not the vault contract address itself. Withdrawing to the contract would irrecoverably lock funds.

**Tasks:**
- Add `require(to != env.current_contract_address())` in `withdraw`
- Return `ContractError::InvalidWithdrawDestination`
- Add a test for self-withdrawal rejection

---

### 104. Add Secret Storage Audit for `.env` Files in CI
**Labels:** `security`, `infrastructure`
**Priority:** High
**Estimated Time:** 1 hour

**Description:**
There is no automated check to prevent real secrets from being committed in `.env` files. A developer could accidentally commit API keys.

**Tasks:**
- Add `trufflehog` or `gitleaks` to the CI pipeline
- Configure to scan staged files on PR
- Add a `.gitleaks.toml` with any false-positive exceptions
- Document the secret scanning process in `CONTRIBUTING.md`

---

### 105. Implement Emergency Vault Freeze by Admin
**Labels:** `security`, `admin`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
The admin can pause the entire contract but cannot freeze a single vault. If a specific vault is compromised, the only option is a global pause affecting all users.

**Tasks:**
- Add `DataKey::VaultFrozen(u64)` boolean flag
- Implement `freeze_vault(env, vault_id)` and `unfreeze_vault(env, vault_id)` — admin-only
- Check the frozen flag in `deposit`, `withdraw`, `check_in`, and `trigger_release`
- Return `ContractError::VaultFrozen`
- Add tests for freeze, operation rejection, and unfreeze

---

### 106. Add Input Sanitization for Metadata `Bytes` Fields
**Labels:** `security`, `vault-core`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
Vault metadata accepts arbitrary bytes. While Soroban doesn't execute metadata, arbitrary bytes in event payloads can break off-chain indexers that expect UTF-8 strings.

**Tasks:**
- Optionally validate metadata bytes as valid UTF-8 when set via `set_metadata` or `update_metadata`
- Add a `require_utf8_metadata: bool` flag to `ProtocolConfig`
- Return `ContractError::InvalidMetadataEncoding` for non-UTF-8 bytes when the flag is set
- Add tests for both enforcement modes

---

## Performance

### 107. Benchmark `trigger_release` Instruction Usage vs. Beneficiary Count
**Labels:** `performance`, `vault-core`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
There is no benchmark measuring how `trigger_release` instruction count scales with beneficiary count. The function could silently fail on-chain for large beneficiary lists.

**Tasks:**
- Add benchmarks in `docs/benchmarking-guide.md` for 1, 5, 10, 20, 50 beneficiaries
- Measure using Soroban's `budget()` API in tests
- Derive the maximum safe beneficiary count before hitting the instruction limit
- Add a runtime guard rejecting beneficiary counts above the safe maximum

---

### 108. Optimize `get_check_in_history_page` to Avoid Full Deserialization
**Labels:** `performance`, `vault-core`
**Priority:** Low
**Estimated Time:** 2 hours

**Description:**
The check-in history is stored as a `Vec<CheckInHistoryEntry>`. Fetching a single page requires deserializing the entire vector, which is expensive for long-lived vaults.

**Tasks:**
- Evaluate changing storage to individual `DataKey::CheckInEntry(vault_id, index)` entries
- Implement paginated access without full deserialization
- Measure instruction savings with a 100-entry history
- Update tests to cover the new storage layout

---

### 109. Implement Lazy TTL Extension to Avoid Per-Read Storage Writes
**Labels:** `performance`, `vault-core`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
`get_vault` extends the vault's TTL on every read. This means every read call is a write call, consuming extra instructions and fees.

**Tasks:**
- Change `get_vault` to only extend TTL if the remaining TTL is below `VAULT_TTL_THRESHOLD`
- This avoids writes on hot-read paths
- Add tests confirming TTL is extended when below threshold and not extended when above

---

## Developer Experience

### 110. Add `make` / Task Runner Targets for Common Development Commands
**Labels:** `developer-experience`, `infrastructure`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
Developers must memorize multiple `cargo`, `stellar`, and `./scripts/` commands. A `Makefile` or `just` justfile would centralize common tasks.

**Tasks:**
- Create a `Justfile` (or `Makefile`) with targets: `build`, `test`, `clippy`, `audit`, `deploy-testnet`, `deploy-mainnet`, `docker-up`, `docker-down`
- Document usage in `README.md`
- Add a `just --list` output to `CONTRIBUTING.md`

---

### 111. Add VS Code `launch.json` for Rust Contract Debugging
**Labels:** `developer-experience`, `tooling`
**Priority:** Low
**Estimated Time:** 1 hour

**Description:**
There are no VS Code debugging configurations. Developers cannot set breakpoints in contract code without manually configuring `rust-analyzer` and `lldb`.

**Tasks:**
- Add `.vscode/launch.json` with a `cargo test` debug configuration
- Add `.vscode/settings.json` with `rust-analyzer` settings for the workspace
- Document the debugging workflow in `CONTRIBUTING.md`

---

### 112. Add `clippy` Lint Configuration File
**Labels:** `developer-experience`, `quality`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
The CI runs `cargo clippy` without a configuration file. Lint rules are inconsistently applied across crates and developers see different warnings locally vs. CI.

**Tasks:**
- Create `.clippy.toml` or use `#![deny(...)]` annotations consistently across crates
- Add `clippy::pedantic` with selective allows for accepted patterns
- Document the lint policy in `CONTRIBUTING.md`
- Ensure CI fails on any remaining clippy warning

---

### 113. Add `rustfmt` Configuration File
**Labels:** `developer-experience`, `quality`
**Priority:** Low
**Estimated Time:** 15 minutes

**Description:**
There is no `rustfmt.toml` in the project. Different developers use different formatting settings, causing noisy diffs.

**Tasks:**
- Create `rustfmt.toml` with project-wide formatting settings
- Run `cargo fmt --check` in CI and fail on formatting differences
- Add a note in `CONTRIBUTING.md` to run `cargo fmt` before committing

---

### 114. Create `ARCHITECTURE.md` Top-Level Overview Document
**Labels:** `documentation`, `developer-experience`
**Priority:** Medium
**Estimated Time:** 2 hours

**Description:**
`docs/architecture.md` exists but is minimal (1436 bytes). New contributors cannot understand how the contract, backend, and mobile layers interact without reading all source files.

**Tasks:**
- Expand `docs/architecture.md` with:
  - Component diagram (contract ↔ backend ↔ mobile ↔ Stellar network)
  - Data flow for the check-in and release flows
  - Technology choices and rationale
  - Links to per-component docs
- Add a mermaid sequence diagram for the full vault lifecycle

---

### 115. Add `CHANGELOG.md` and Semantic Versioning Policy
**Labels:** `developer-experience`, `infrastructure`
**Priority:** Medium
**Estimated Time:** 1 hour

**Description:**
There is no `CHANGELOG.md` and no versioning policy. Users cannot determine what changed between contract versions, and the `get_contract_version` function has nothing meaningful to return.

**Tasks:**
- Create `CHANGELOG.md` with an initial entry for v1.0.0
- Document the versioning policy in `CONTRIBUTING.md` (semver for contract ABI, calver for releases)
- Update `get_contract_version` to return a value consistent with `CHANGELOG.md`
- Add a CI check that the version in contract code matches `CHANGELOG.md`

---

### 116. Add Example `.env` Values for All Mobile Configuration Variables
**Labels:** `developer-experience`, `mobile`
**Priority:** Low
**Estimated Time:** 30 minutes

**Description:**
`.env.example` only documents backend and contract variables. Mobile developers must discover required environment variables from the source code.

**Tasks:**
- Add mobile-specific entries to `.env.example`: `VITE_STELLAR_NETWORK`, `ANDROID_STELLAR_RPC_URL`, `IOS_STELLAR_RPC_URL`, etc.
- Add comments explaining each variable's purpose
- Verify all env variables read by mobile code are documented

---

### 117. Implement Contract Version Compatibility Check on Backend Startup
**Labels:** `enhancement`, `backend`, `infrastructure`
**Priority:** High
**Estimated Time:** 2 hours

**Description:**
The backend connects to a deployed contract but does not verify the contract version is compatible. A contract upgrade could change function signatures and break the backend silently.

**Tasks:**
- On backend startup, call `get_contract_version` on the configured contract address
- Compare the returned version against a `MIN_CONTRACT_VERSION` config value
- Refuse to start if the contract version is below the minimum
- Log the contract version on every startup
- Add tests for compatible, incompatible, and unreachable contract scenarios

---

## Summary

These 117 issues span:
- **Smart Contract — Vault Core:** 10 issues
- **Smart Contract — TTL & Check-In:** 6 issues
- **Smart Contract — Passkey & Auth:** 4 issues
- **Smart Contract — Beneficiary & Release:** 10 issues
- **Smart Contract — Multi-Sig:** 5 issues
- **Smart Contract — Vesting:** 5 issues
- **Smart Contract — Ownership Transfer:** 3 issues
- **Smart Contract — Admin & Protocol:** 7 issues
- **Smart Contract — ZK Verifier:** 3 issues
- **Backend — API & Handlers:** 7 issues
- **Backend — Notifications & Reminders:** 5 issues
- **Backend — WebSocket:** 3 issues
- **Backend — Database:** 2 issues
- **Mobile — Android:** 5 issues
- **Mobile — iOS:** 5 issues
- **Testing & Quality:** 8 issues
- **Documentation:** 6 issues
- **Infrastructure & DevOps:** 6 issues
- **Security:** 6 issues
- **Performance:** 3 issues
- **Developer Experience:** 7 issues

**Total Estimated Effort:** ~170–200 hours

**Recommended Priority Order:**
1. Critical/Security (27, 101, 102, 103, 104, 105)
2. High-priority bugs (4, 5, 10, 15, 22, 25, 32, 37, 39, 48, 54, 58, 59)
3. High-priority features (2, 23, 35, 44, 51, 71, 76, 79, 83, 95, 100, 107, 117)
4. Medium-priority enhancements
5. Low-priority and developer experience improvements
