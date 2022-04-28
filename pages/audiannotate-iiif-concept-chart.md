---
layout: default
title: AudiAnnotate IIIF Concept Chart
permalink: audiannotate-iiif-concept-chart
---
<!-- Add an essay or interpretive material below this line,
using HTML or markdown.  Do not modify this file above this line -->

<html>
  <body>
    
    <table>
      <tr>
        <th>AudiAnnotate</th>
        <th>IIIF</th>
        <th>Aviary</th>
        <th>Notes</th>
        <th>Examples</th>
      </tr>
      <tr>
        <td>Item</td>
        <td>Canvas</td>
        <td>File</td>
        <td>Could have more than one media file but practically does not; Two media files would be two canvases (see example) on one manifest.</td>
        <td><a href="https://universalviewer.io/examples/#?c=&m=&s=&cv=&manifest=https%3A%2F%2Fiiif-commons.github.io%2Fiiif-av-component%2Fexamples%2Fdata%2Fbl%2Fsounds-tests%2Floose-ends%2FC1685_98_P3.json&rid=">Universal Viewer example</a></td>
      </tr>
       <tr>
        <td>One or more file(s) that we annotate</td>
        <td>Manifest</td>
        <td>Resource</td>
        <td>Must have a Canvas; may contain more than one Canvas</td>
        <td>Three interviews by a single Holocaust survivor; two sides of one tape</td>
      </tr>
       <tr>
        <td>Annotation: Timestamped text commentary on AV</td>
        <td>A W3C-compliant file aggregating annotations, associated with a manifest</td>
        <td></td>
        <td></td>
         <td><a href="https://kywark.github.io/gentle-improvement/">SENT example</a>; all the annotations identifying environmental noise for one recording; another annotation page might have technical sounds</td>
      </tr>
       <tr>
        <td>An annotation layer: Aggregate collection of annotation pages in one or across multiple manifests or canvases</td>
        <td>W3C annotation collections (bag)</td>
        <td>Annotation page type label</td>
        <td>Conceptually: A means of organizing annotations by category. Multiple audio files have the same kinds of annotations across them.</td>
        <td>Multiple environmental annotation pages associated with multiple Canvases or manifests</td>
      </tr>
       <tr>
        <td>Projects, editions, exhibition – multiple Manifests associated with one GitHub repository</td>
        <td>Collections: assembly of one or more than one manifest into a IIIF JSON file</td>
        <td>TBD</td>
        <td>A set of related AV materials with contextual information (e.g., front matter, explicatory prose</td>
        <td><a href="https://tanyaclement.github.io/znh_jacksonville_1939/">Example AudiAnnotate Project</a></td>
      </tr>
       <tr>
        <td>TBD</td>
        <td>Structures – an index or a TOC for a single manifest; a structure can span multiple canvases</td>
        <td></td>
        <td>An array with a range and a label and a list of items (which also have ranges so can be nested)</td>
        <td><a href="https://iiif-commons.github.io/iiif-av-component/examples/data/bl/sounds-tests/loose-ends/C1685_98_P3.json">IIIF manifest example</a>; <a href="https://universalviewer.io/examples/#?c=&m=&s=&cv=1&manifest=https%3A%2F%2Fiiif-commons.github.io%2Fiiif-av-component%2Fexamples%2Fdata%2Fbl%2Fsounds-tests%2Floose-ends%2FC1685_98_P3.json&rid=https%3A%2F%2Fapi.bl.uk%2Fmetadata%2Fiiif%2Fark%3A%2F81055%2Fvdc_100052359795.0x00000e">Universal Viewer example</a></td>
      </tr>
    </table>
