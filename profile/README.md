<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Albumentations — open-source image augmentation ecosystem for computer vision">
</p>

<p align="center">
  <a href="https://albumentations.ai/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=org_profile"><img src="https://img.shields.io/badge/Website-albumentations.ai-5b2fc4?style=for-the-badge" alt="Albumentations website"></a>
  <a href="https://albumentations.ai/docs/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=org_profile"><img src="https://img.shields.io/badge/Documentation-Read_the_docs-1267d7?style=for-the-badge" alt="Documentation"></a>
  <a href="https://albumentations.ai/explore/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=org_profile"><img src="https://img.shields.io/badge/Explore-Try_transforms-16825d?style=for-the-badge" alt="Explore transforms"></a>
  <a href="https://github.com/sponsors/albumentations-team"><img src="https://img.shields.io/badge/Sponsor-Support_maintenance-ea4aaa?style=for-the-badge&amp;logo=githubsponsors&amp;logoColor=white" alt="Sponsor Albumentations"></a>
</p>

Albumentations is a widely adopted open-source image-augmentation ecosystem for
computer vision. It helps engineers and researchers create valid training
variation while keeping images, masks, bounding boxes, keypoints, volumes, and
video frames synchronized.

## Start new work with AlbumentationsX

[AlbumentationsX](https://github.com/albumentations-team/AlbumentationsX) is the
actively developed library in the ecosystem. Install it with OpenCV for
headless servers and training environments:

```bash
pip install "albumentationsx[headless]"
```

The package preserves the familiar `albumentations` import path:

```python
import albumentations as A

transform = A.Compose(
    [
        A.RandomCrop(height=256, width=256),
        A.HorizontalFlip(p=0.5),
        A.RandomBrightnessContrast(p=0.2),
    ]
)

augmented = transform(image=image, mask=mask)
```

Use the [documentation](https://albumentations.ai/docs/?utm_source=github&utm_medium=referral&utm_campaign=org_profile)
for guides and API details, or open [Explore](https://albumentations.ai/explore/?utm_source=github&utm_medium=referral&utm_campaign=org_profile)
to test transforms in the browser.

## The ecosystem

| Project | What it provides |
| --- | --- |
| [**AlbumentationsX**](https://github.com/albumentations-team/AlbumentationsX) | Actively developed augmentation pipelines for images and synchronized annotations. |
| [**Albucore**](https://github.com/albumentations-team/albucore) | Optimized atomic image-processing functions with workload-aware backend selection. |
| [**albu-spec**](https://github.com/albumentations-team/albu-spec) | Structured, typed metadata extracted from AlbumentationsX transforms. |
| [**Benchmark suite**](https://github.com/albumentations-team/benchmark) | Reproducible image, multichannel, video, and DataLoader comparisons. |
| [**Examples**](https://github.com/albumentations-team/albumentations_examples) | Runnable notebooks for classification, segmentation, detection, keypoints, replay, serialization, and integrations. |
| [**Albumentations**](https://github.com/albumentations-team/albumentations) | The MIT-licensed legacy library, preserved for reproducibility, continued use, and forks. |

## Public adoption

<table>
  <tr>
    <td align="center"><strong>160.7M</strong><br>PyPI downloads</td>
    <td align="center"><strong>15.3k</strong><br>GitHub stars</td>
    <td align="center"><strong>40k+</strong><br>GitHub-reported public dependents</td>
    <td align="center"><strong>2,270</strong><br>citing research works</td>
  </tr>
</table>

These figures describe public ecosystem adoption, not paid customers or
endorsements. Downloads were checked on
[pepy.tech](https://pepy.tech/projects/albumentations),
[stars](https://github.com/albumentations-team/albumentations/stargazers) and
[public dependents](https://github.com/albumentations-team/albumentations/network/dependents)
on GitHub, and [research works](https://albumentations.ai/adoption/papers/) in
the deduplicated adoption snapshot on 22 July 2026. Browse the wider
[public adoption evidence](https://albumentations.ai/adoption/).
Albumentations is a
[NumFOCUS Affiliated Project](https://numfocus.org/sponsored-projects/affiliated-projects).

## Licensing

Components of the ecosystem use different licenses. The legacy
[`albumentations`](https://github.com/albumentations-team/albumentations)
package and repository remain available under the MIT License. The current
[`albumentationsx`](https://github.com/albumentations-team/AlbumentationsX)
package and repository are available under AGPL-3.0-only.

The AGPL permits commercial use subject to its terms. Albumentations, LLC also
offers [separately negotiated commercial licenses for AlbumentationsX](https://albumentations.ai/pricing?utm_source=github&utm_medium=referral&utm_campaign=org_profile),
with alternative rights defined by the applicable agreement. Whether a
particular use complies with the AGPL depends on the deployment facts.

## Join the project

- Read the [contribution guide](https://github.com/albumentations-team/AlbumentationsX/blob/main/CONTRIBUTING.md) and help improve AlbumentationsX.
- Ask usage questions and meet other practitioners on [Discord](https://discord.gg/AKPrrDYNAt).
- Follow releases and tutorials through the [newsletter](https://albumentations.ai/subscribe?utm_source=github&utm_medium=referral&utm_campaign=org_profile).
- Support long-term maintenance through [GitHub Sponsors](https://github.com/sponsors/albumentations-team).

<p align="center">
  <a href="https://github.com/albumentations-team/AlbumentationsX">Code</a>
  ·
  <a href="https://albumentations.ai/docs/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=org_profile">Docs</a>
  ·
  <a href="https://albumentations.ai/explore/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=org_profile">Explore</a>
  ·
  <a href="https://albumentations.ai/docs/benchmarks/image-benchmarks/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=org_profile">Benchmarks</a>
  ·
  <a href="https://github.com/sponsors/albumentations-team">Sponsor</a>
</p>
