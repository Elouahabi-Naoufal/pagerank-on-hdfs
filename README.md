<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs">
    <h3 align="center">PageRank on HDFS</h3>
  </a>

  <p align="center">
    Planned PageRank implementation with MapReduce on YARN and HDFS.
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs"><strong>Explore the repository »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/issues/new?labels=bug">Report Bug</a>
    &middot;
    <a href="https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/issues/new?labels=enhancement">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul><li><a href="#built-with">Built With</a></li></ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This repository is the project space for a fourth-year PFM project at EMSI (semester S2): implement PageRank as a distributed MapReduce workload on Hadoop.

The intended work is a graph stored on HDFS, iterative MapReduce jobs submitted to YARN, and a convergence check between iterations. The repository is currently a scaffold: it contains only a `.gitkeep` placeholder and no implementation.

* Storage: HDFS.
* Execution: MapReduce jobs on YARN.
* Algorithm: iterative PageRank with a convergence threshold.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This repository is currently a scaffold, so no stack is wired up yet. The planned stack is:

* [![Apache Hadoop][hadoop-badge]][hadoop-url]
* [![HDFS][hdfs-badge]][hdfs-url]
* [![Apache YARN][yarn-badge]][yarn-url]
* [![MapReduce][mapreduce-badge]][mapreduce-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

The repository has no runnable code yet. The steps below only set up a local checkout for future work.

### Prerequisites

* Git
* The toolchain for the planned stack, installed when the implementation starts.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs.git
   cd pagerank-on-hdfs
   ```

2. There is nothing to install or start at this stage.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

There is no executable code in this repository. It currently serves as the project space for the
work described above; the usage instructions will be added together with the implementation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] Create the repository scaffold.
- [ ] Define the input graph format and a sample dataset.
- [ ] Implement the mapper and reducer for one PageRank iteration.
- [ ] Add the driver that repeats iterations until convergence.
- [ ] Run the job on a multi-node or pseudo-distributed cluster and document the results.

See the [open issues](https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

<a href="https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Elouahabi-Naoufal/pagerank-on-hdfs" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This project is not licensed — all rights reserved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Naoufal Elouahabi - [LinkedIn](https://www.linkedin.com/in/elouahabi-naoufal/) - elouahabi-naoufal1@gmail.com

Project Link: [https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs](https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* [Apache Hadoop MapReduce Tutorial](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html)
* [PageRank paper: The PageRank Citation Ranking](http://ilpubs.stanford.edu:8090/422/)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Elouahabi-Naoufal/pagerank-on-hdfs.svg?style=for-the-badge
[contributors-url]: https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Elouahabi-Naoufal/pagerank-on-hdfs.svg?style=for-the-badge
[forks-url]: https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/network/members
[stars-shield]: https://img.shields.io/github/stars/Elouahabi-Naoufal/pagerank-on-hdfs.svg?style=for-the-badge
[stars-url]: https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/stargazers
[issues-shield]: https://img.shields.io/github/issues/Elouahabi-Naoufal/pagerank-on-hdfs.svg?style=for-the-badge
[issues-url]: https://github.com/Elouahabi-Naoufal/pagerank-on-hdfs/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/elouahabi-naoufal/
[hadoop-badge]: https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black
[hadoop-url]: https://hadoop.apache.org/
[hdfs-badge]: https://img.shields.io/badge/HDFS-0A7E8C?style=for-the-badge&logo=apachehadoop&logoColor=white
[hdfs-url]: https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html
[yarn-badge]: https://img.shields.io/badge/Apache%20YARN-0A7E8C?style=for-the-badge&logo=apachehadoop&logoColor=white
[yarn-url]: https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/YARN.html
[mapreduce-badge]: https://img.shields.io/badge/MapReduce-0A7E8C?style=for-the-badge&logo=apachehadoop&logoColor=white
[mapreduce-url]: https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html
