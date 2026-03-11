# Clustering_Spotify_Songs
Cluster Spotify tracks by audio features using KMeans, PCA, and t-SNE.

## Dataset
[Ultimate Spotify Tracks DB](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db) — upload `SpotifyFeatures.csv` directly in Colab.

## Features Used
`danceability` · `energy` · `tempo` · `loudness` · `valence`

## Steps
1. Load & clean CSV
2. Normalize with StandardScaler
3. Find optimal K (Elbow + Silhouette)
4. Train KMeans
5. Visualize with PCA & t-SNE
6. Profile clusters via Radar Chart

## Visualizations
| Plot | Purpose |
| Elbow + Silhouette | Choose best K |
| PCA Scatter | Global cluster structure |
| t-SNE Scatter | Local cluster patterns |
| Radar Chart | Audio fingerprint per cluster |

## Typical Cluster Insights
| Cluster | Pattern |
| 🕺 High dance + valence | Pop / Dance |
| 🤘 High energy + loud | Rock / Metal |
| 😌 Low energy + tempo | Acoustic / Ambient |
| ⚡ High tempo + low valence | EDM / Electronic |
| 🎷 Balanced features | Jazz / R&B |

## Requirements
`pandas` `numpy` `scikit-learn` `matplotlib` — all pre-installed in Colab.

## Requirements
`pandas` `numpy` `scikit-learn` `matplotlib` — all pre-installed in Colab.
