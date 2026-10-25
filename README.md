# Zcash Developer Quests

Participant: **papytee** (GitHub: PapyT).

## Developer Verification

Requires Python 3.8+ and Git. No packages or credentials are needed.

```sh
git clone https://github.com/PapyT/zcash-developer-quests.git
cd zcash-developer-quests
python3 developer_verification.py
```

On Windows, use `py developer_verification.py` if `python3` is unavailable.

Each run prints the participant name, the actual execution timestamp in UTC, and a newly generated 128-bit random value. `datetime.now(timezone.utc)` supplies the time; `secrets.token_hex(16)` produces 16 random bytes displayed as 32 hexadecimal characters.

This initial exercise verifies the development workflow. It does not make a Zcash transaction.

## AI assistance

Prepared with ChatGPT assistance. The participant should run the program and review the code before explaining or submitting it.
