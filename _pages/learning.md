---
layout: page
permalink: /learning/
title: learning
description: Links to great course materials I have followed in the past.
datatable: true
nav: true
order: 4
---

<table id="tabled_id" class="display">
    <thead>
        <tr>
            <th>Name</th>
            <th>Platform</th>
            <th>Details</th>
            <th>Link</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Python for Everybody Specialisation</td>
            <td>Coursera</td>
            <td>Good for Introduction to Python and even for newbie programmers</td>
            <td><a href="https://www.coursera.org/specializations/python">Python for Everybody</a></td>
        </tr>
        <tr>
            <td>CS61C - Machine Structures (Great Ideas in Computer Architecture)</td>
            <td>UC Berkeley EECS</td>
            <td>Covers a large array of topics from C programming to RISC-V and modern day computer architecture concepts</td>            
            <td><a href="https://cs61c.org">61C</a></td>
        </tr>
        <tr>
            <td>VSD - Pipelining RISC-V with Transaction-Level Verilog</td>
            <td>Udemy</td>
            <td>Introduction to the revolutionary and upcoming Transaction-Level Verilog (by Steve Hoover, my GSoC '20 mentor)</td>            
            <td><a href="https://www.udemy.com/course/vsd-pipelining-risc-v-with-transaction-level-verilog/">Udemy</a></td>
        </tr>
        <tr>
            <td>Customising a RISC-V Core</td>
            <td>Graham Markall, OSHCamp 2019</td>
            <td>Great resource for understanding the structure of the RI5CY (CV32E40P) RISC-V core from ETH Zurich/OpenHW Group</td>            
            <td><a href="https://gmarkall.wordpress.com/teaching/">Website</a></td>
        </tr>
    </tbody>
</table>

<script type="text/javascript">
window.onload = function()
{
    $('#tabled_id').DataTable({
        paging: true,
        searching: true,
        autoWidth: true
        }); 
}
</script>
