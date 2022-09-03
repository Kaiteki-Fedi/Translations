# Translations

This repository contains the UI strings used in Kaiteki. The translations are in the [ARB (application resource bundle) format](https://github.com/google/app-resource-bundle).

About English translations: Kaiteki uses US English, a British version can be added under a separate file (`app_en_gb.arb`).

Contributions are welcome!

[![Translation status](https://wl.craftplacer.moe/widgets/kaiteki/-/multi-auto.svg)](https://wl.craftplacer.moe/engage/kaiteki/)

## A note about terminology

Kaiteki uses generalized terms that don't adhere to a specific social media platform. Here below you will find a table of the different terms Kaiteki uses compared to other platforms.

<table>
    <thead>
        <tr>
            <th>Kaiteki</th>
            <th>Mastodon</th>
            <th>Pleroma</th>
            <th>Misskey</th>
            <th>Twitter</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <b>Post</b><br>
                <span>Something that the user uploads</span>
            </td>
            <td>Toot</td>
            <td>Status</td>
            <td>Note</td>
            <td>Tweet</td>
        </tr>
    </tbody>
</table>

### Scopes, visibility
<table>
    <thead>
        <tr>
            <th>Kaiteki</th>
            <th>Mastodon</th>
            <th>Pleroma</th>
            <th>Misskey</th>
            <th>Twitter</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <b>Public</b><br>
                <span>A post that is accessible to everyone</span>
            </td>
            <td colspan="3">Public</td>
            <td>Everyone</td>
        </tr>
        <tr>
            <td>
                <b>Unlisted</b><br>
                <span>Like public, but post doesn't appear on public timelines</span>
            </td>
            <td colspan="2">Unlisted</td>
            <td>Home</td>
            <td rowspan="3">-</td>
        </tr>
        <tr>
            <td><b>Followers-only</b></td>
            <td colspan="3">Followers-only</td>
        </tr>
        <tr>
            <td>
                <b>Direct</b><br>
                <span>A post that is only accessible to the people mentioned inside</span>
            </td>
            <td>Mentioned people only</td>
            <td colspan="2">Direct</td>
        </tr>
    </tbody>
</table>

### Timelines
<table>
    <thead>
        <tr>
            <th>Kaiteki</th>
            <th>Mastodon</th>
            <th>Pleroma</th>
            <th>Misskey</th>
            <th>Twitter</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <b>Home</b><br>
                <span>Posts from the people you follow</span>
            </td>
            <td colspan="4">Home</td>
        </tr>
        <tr>
            <td>
                <b>Local</b><br>
                <span>Public posts from your local instance</span>
            </td>
            <td>Local</td>
            <td>Public timeline</td>
            <td>Local</td>
            <td rowspan="2">-</td>
        </tr>
        <tr>
            <td>
                <b>Federated</b><br>
                <span>Public posts from federated instances</span>
            </td>
            <td>Federated</td>
            <td>Known Network</td>
            <td>Global</td>
        </tr>
    </tbody>
</table>

### Interaction
<table>
    <thead>
        <tr>
            <th>Kaiteki</th>
            <th>Mastodon</th>
            <th>Pleroma</th>
            <th>Misskey</th>
            <th>Twitter</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <b>Favorite</b><br>
                <span>The user likes this post</span>
            </td>
            <td>Favourite</td>
            <td>Favorite</td>
            <td>-</td>
            <td>Like</td>
        </tr>
        <tr>
            <td>
                <b>Repeat</b><br>
                <span>The user spreads the post</span>
            </td>
            <td>Boost</td>
            <td>Repeat</td>
            <td>Renote</td>
            <td>Retweet</td>
        </tr>
        <tr>
            <td>
                <b>React(ion)</b><br>
                <span>The user reacts with an emoji on the post</span>
            </td>
            <td>-</td>
            <td colspan="2">React</td>
            <td>-</td>
        </tr>
    </tbody>
</table>
