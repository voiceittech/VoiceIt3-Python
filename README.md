<img src="https://raw.githubusercontent.com/voiceittech/voiceit3-python/main/python.png" width="100%" style="width:100%" />

[![API Test](https://github.com/voiceittech/voiceit3-python/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/voiceittech/voiceit3-python/actions/workflows/test.yml)
[![Dependabot](https://img.shields.io/github/issues-pr/voiceittech/voiceit3-python/dependencies?label=dependabot&logo=dependabot&color=025e8c)](https://github.com/voiceittech/voiceit3-python/pulls?q=is%3Apr+label%3Adependencies)
[![Version](https://img.shields.io/badge/version-3.0.12-blue)](https://github.com/voiceittech/voiceit3-python)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/voiceittech/voiceit3-python/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/platform-Python-lightgrey)](https://github.com/voiceittech/voiceit3-python)
[![VoiceIt API](https://img.shields.io/badge/VoiceIt-API%203.0-blue)](https://voiceit.io)


A Python wrapper for VoiceIt's API 3.0 featuring Voice + Face Verification and Identification.

## Features

This SDK wraps the full VoiceIt API 3.0 surface:

- **User management** — create, fetch, check existence, and delete users; list the groups a user belongs to
- **Sub-account management** — create and manage sub-accounts under a parent account
- **Group management** — create, fetch, check, and delete groups; add and remove users
- **Voice, Face & Video enrollment** — enroll from a local file or a remote URL (including split-video)
- **Voice, Face & Video verification** — 1:1 authentication from file or URL
- **Voice & Video identification** — 1:N matching of a sample against everyone in a group
- **Phrase management** — list the enrollment phrases available for a content language
- **Notification webhooks** — register/remove callback URLs to receive asynchronous results
- **Passive liveness & deepfake detection** — performed automatically by the API on face/video calls (API 3.0)

See the [HTTP API 3.0 Documentation](https://voiceit.io/documentation) for per-call parameters and response codes.

## Installation

```bash
git clone https://github.com/voiceittech/voiceit3-python.git
```

Then import in your project:
```python
from voiceit3 import VoiceIt3
```

## Getting Started

Sign up at [voiceit.io/pricing](https://voiceit.io/pricing) to get your API Key and Token, then log in to the [Dashboard](https://dashboard.voiceit.io) to manage your account.

<img src="https://raw.githubusercontent.com/voiceittech/voiceit3-python/main/Graphics/getcredentials.png" alt="API Key and Token" width="400px" />

## API Calls

You can visit our [HTTP API 3.0 Documentation](https://voiceit.io/documentation) for detailed information on each API call.

## Support

If you find this SDK useful, please consider giving it a star on GitHub — it helps others discover the project!

[![GitHub stars](https://img.shields.io/github/stars/voiceittech/voiceit3-python?style=social)](https://github.com/voiceittech/voiceit3-python/stargazers)

## License

voiceit3-python is available under the MIT license. See the LICENSE file for more info.

