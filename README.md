<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>List of Books</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://mottie.github.io/tablesorter/js/jquery.tablesorter.js"></script>
    <style>
        body {
            background: linear-gradient(to right, #CC0000, #F4C430);
            font-family: 'Arial', sans-serif;
        }
        /* Hover effect for rows */
        tr:hover {
            background-color: #0047AB !important;
            color: white;
            cursor: pointer;
        }
        /* Mobile Responsive Style for Cards */
        @media (max-width: 768px) {
            table thead {
                display: none;
            }
            table, table tbody, table tr, table td {
                display: block;
                width: 100%;
            }
            table tr {
                margin-bottom: 15px;
                border: 1px solid #ddd;
                border-radius: 10px;
                background-color: #fff;
                overflow: hidden;
                padding: 15px;
            }
            table td {
                text-align: right;
                padding-left: 50%;
                position: relative;
            }
            table td::before {
                content: attr(data-label);
                position: absolute;
                left: 15px;
                font-weight: bold;
                text-transform: uppercase;
            }
        }
    </style>
</head>
<body>

    <div class="container py-5">
        <div class="table-responsive">
            <table id="myTable" class="table table-bordered table-hover tablesorter">

                <thead class="table-dark">
                    <tr>
                        <th scope="col">Book Title</th>
                        <th scope="col">Author</th>
                        <th scope="col">Publisher</th>
                        
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td data-label="Book Title">Breaking India: Western Interventions In Dravidian And Dalit Faultlines</td>
                        <td data-label="Author">Rajiv Malhotra, Aravindan Neelakandan</td>
                        <td data-label="Publisher">Amaryllis - an Imprint of Manjul Publishing House</td>
                        
                    </tr>
                    <tr>
                        <td data-label="Book Title">Being Different: An Indian Challenge to Western Universalism</td>
                        <td data-label="Author">Rajiv Malhotra</td>
                        <td data-label="Publisher">Harper India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Aavarana: The Veil</td>
                        <td data-label="Author">S. L. Bhyrappa (author), Sandeep Balakrishna (Translator)</td>
                        <td data-label="Publisher">Rupa Publications</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Animal Farm</td>
                        <td data-label="Author">George Orwell</td>
                        <td data-label="Publisher">Penguin India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">1984</td>
                        <td data-label="Author">George Orwell</td>
                        <td data-label="Publisher">SSA Books</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">India: A Wounded Civilization</td>
                        <td data-label="Author">V S Naipaul </td>
                        <td data-label="Publisher">Pan Macmillan</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Da Vinci Code</td>
                        <td data-label="Author">Dan Brown</td>
                        <td data-label="Publisher">Corgi Books</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Life Over Two Beers and Other Stories</td>
                        <td data-label="Author">Sanjeev Sanyal</td>
                        <td data-label="Publisher">Penguin India</td>
                    </tr>

                    
                    <tr>
                        <td data-label="Book Title">The Satanic Verses</td>
                        <td data-label="Author">Salman Rushdie</td>
                        <td data-label="Publisher">Random House Publishing Group</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Lajja</td>
                        <td data-label="Author">Taslima Nasrin (Author), Anchita Ghatak (Translator)</td>
                        <td data-label="Publisher">Penguin India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Among the Believers </td>
                        <td data-label="Author">V.S. Naipaul</td>
                        <td data-label="Publisher">Picador</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Beyond Belief: Islamic Excursions Among the Converted Peoples</td>
                        <td data-label="Author">V.S. Naipaul</td>
                        <td data-label="Publisher">Picador</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Indra's Net</td>
                        <td data-label="Author">Rajiv Malhotra</td>
                        <td data-label="Publisher">Harper Collins India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Academic Hinduphobia: A Critique of Wendy Doniger’s Erotic School of Indology</td>
                        <td data-label="Author">Rajiv Malhotra</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Battle for Sanskrit: Is Sanskrit Political or Sacred? Oppressive or Liberating? Dead or Alive?</td>
                        <td data-label="Author">Rajiv Malhotra</td>
                        <td data-label="Publisher">Harper Collins India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">What Happened to Netaji?</td>
                        <td data-label="Author">Anuj Dhar</td>
                        <td data-label="Publisher">Vitasta Publishing Private Limited</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Urban Naxals: The Making Of Buddha In A Traffic Jam</td>
                        <td data-label="Author">Vivek Agnihotri</td>
                        <td data-label="Publisher">Garuda Prakashan</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Sexual abuse and Culture of Calothicism</td>
                        <td data-label="Author">Myra L Hydalgo</td>
                        <td data-label="Publisher">Routledge</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">The Lost River: On the Trail of the Sarasvatī</td>
                        <td data-label="Author">Michel Danino</td>
                        <td data-label="Publisher">Penguin India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Sri Aurobindo and India's Rebirth</td>
                        <td data-label="Author">Michel Danino(Edited by)</td>
                        <td data-label="Publisher">Rupa Publications India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Your Prime Minister is Dead</td>
                        <td data-label="Author">Anuj Dhar</td>
                        <td data-label="Publisher">Vitasta Publishing Private Limited</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">The Land of Seven Rivers : The history of India's geography</td>
                        <td data-label="Author">Sanjeev Sanyal</td>
                        <td data-label="Publisher">penguin India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">The Idol Theif</td>
                        <td data-label="Author">S. Vijay Kumar</td>
                        <td data-label="Publisher">Juggernaut</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">The Silence We Keep: A Nun's View of the Catholic Priest Scandal</td>
                        <td data-label="Author">Karol Jackowski</td>
                        <td data-label="Publisher">Crown</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">70 Years of Secularism</td>
                        <td data-label="Author">Sandeep Balakrishna</td>
                        <td data-label="Publisher">Indus University</td>
                    </tr>


                    
                    <tr>
                        <td data-label="Book Title">The Case For India</td>
                        <td data-label="Author">Will Durant</td>
                        <td data-label="Publisher">Neha Publishers & Distributors</td>
                    </tr>


                    
                    <tr>
                        <td data-label="Book Title">THE BATTLE FOR RAMA: Case of the Temple at Ayodhya</td>
                        <td data-label="Author">Meenakshi Jain</td>
                        <td data-label="Publisher"></td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">The Accidental Prime Minister: The Making and Unmaking of Manmohan Singh</td>
                        <td data-label="Author">Sanjay Baru</td>
                        <td data-label="Publisher">PENGUIN INDIA</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Antisocial Media: How Facebook Disconnects Us and Undermines Democracy</td>
                        <td data-label="Author">Siva Vaidhyanathan</td>
                        <td data-label="Publisher">OUP USA</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Six Glorious Epochs of Indian History</td>
                        <td data-label="Author">Vinayak Damodar Savarkar</td>
                        <td data-label="Publisher">Abhishek publications</td>
                    </tr>




                    <tr>
                        <td data-label="Book Title">The Goa Inquisition, Being a Quatercentenary Commemoration Study of the Inquisition in India</td>
                        <td data-label="Author">Anant Kakba Priolkar</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>


                  




                    <tr>
                        <td data-label="Book Title">Arise Arjuna: Hinduism Resurgent in a New Century</td>
                        <td data-label="Author">Dr Dawid Frawley</td>
                        <td data-label="Publisher">Bloomsbury India</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">India a wounded civilisation</td>
                        <td data-label="Author">VS Naipaul</td>
                        <td data-label="Publisher">Pan Macmillan</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">An Area of Darkness: His Discovery of India</td>
                        <td data-label="Author">VS Naipaul</td>
                        <td data-label="Publisher">Picador</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">India: A Million Mutinies Now</td>
                        <td data-label="Author">VS Naipaul</td>
                        <td data-label="Publisher">Picador</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">The Educational Heritage of Ancient India : How an Ecosystem of Learning Was Laid to Waste </td>
                        <td data-label="Author">Sahana Singh</td>
                        <td data-label="Publisher">Notion Press</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">The Tragic Story of Partition</td>
                        <td data-label="Author">H. V. Seshadri</td>
                        <td data-label="Publisher">Sahitya Sindhu Prakashan</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">What Is Hinduism? A Guide for the Global Mind</td>
                        <td data-label="Author">Dr Dawid Frawley</td>
                        <td data-label="Publisher">Bloomsbury India
                        </td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Thank you India ( A German Woman's Journey To The Wisdom of Yoga)</td>
                        <td data-label="Author">Maria Writh</td>
                        <td data-label="Publisher">Generic</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Tipu As He Really Was</td>
                        <td data-label="Author">Gajanan Bhaskar Mehendale</td>
                        <td data-label="Publisher">Samvit Prakashan and Media Pvt Ltd</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Idolatry and the Colonial Idea of India: Visions of Horror, Allegories of Enlightenment</td>
                        <td data-label="Author">Swagato Ganguly</td>
                        <td data-label="Publisher">Routledge India</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">The Heathen in His Blindness: Asia, the West and the Dynamic of Religion</td>
                        <td data-label="Author">S. N. Balagangadhara</td>
                        <td data-label="Publisher">Manohar Pubns</td>
                    </tr>


                
                    <tr>
                        <td data-label="Book Title">Shivaji: His Life and Times</td>
                        <td data-label="Author">Gajanan Bhaskar Mehendale </td>
                        <td data-label="Publisher">Param Mitra Publications</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">Sati Evangelicals Baptist Missionaries and the Changing</td>
                        <td data-label="Author">Meenakshi Jain </td>
                        <td data-label="Publisher">Aryan Books International</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">The Man Who Saved India</td>
                        <td data-label="Author">Hindol Sengupta</td>
                        <td data-label="Publisher">PENGUIN VIKING</td>
                    </tr>


                    <tr>
                        <td data-label="Book Title">RAMA AND AYODHYA</td>
                        <td data-label="Author">Meenakshi Jain</td>
                        <td data-label="Publisher">Aryan Books International</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Amen: The Autobiography of a Nun</td>
                        <td data-label="Author">Sister Jesme</td>
                        <td data-label="Publisher">Penguin</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Antaryoga</td>
                        <td data-label="Author">Sri Anirvan, translation from Bangla by Gaurisankar Mohta, introduction by Ram Swarup</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">The Aryan Invasion Theory and Indian Nationalism</td>
                        <td data-label="Author">Talageri</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Ayodhya: The Case Against the Temple</td>
                        <td data-label="Author">Koenraad Elst</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Catholic Ashrams: Sannyasins or Swindlers?</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Calcutta Quran Petition</td>
                        <td data-label="Author">Chandmal Chopra (author), Sita Ram Goel (Editor)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Communal Violence and propaganda</td>
                        <td data-label="Author">Koenraad Elst</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Concept of Hindu Nation</td>
                        <td data-label="Author">Abhas Chatterjee</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Defence of Hindu society</td>
                        <td data-label="Author">Goel, Sita Ram </td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Demographic Siege</td>
                        <td data-label="Author">Koenraad Elst</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Freedom of Expression: Secular Theocracy versus Liberal Democracy</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Genesis and Growth of Nehruism - Vol.1: Commitment to Communism</td>
                        <td data-label="Author">Goel Sita Ram (Author)</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Heroic Hindu resistance to Muslim invaders, 636 AD to 1206 AD</td>
                        <td data-label="Author">Sita Ram Goel (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Hindu Phenomenon</td>
                        <td data-label="Author">Girilal Jain (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Hindu society under siege</td>
                        <td data-label="Author">Goel Ram Sita (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Hindu Temples: What happened to them, Vol.1: A Preliminary Survey</td>
                        <td data-label="Author">Sita Ram Goel (compiled and edited)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Hindu Temples: What Happened to Them, Vol.2: The Islamic Evidence </td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Hinduism and Monotheistic Religions, Foreword by David Frawley (Vamadeva Shastri) </td>
                        <td data-label="Author">Ram Swarup</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Hindu View of Christianity and Islam</td>
                        <td data-label="Author">Ram Swarup</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Hindus and Hinduism: manipulation of meanings</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">History of Hindu-Christian Encounters (AD 304 to 1996)</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">How I Became A Hindu</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">India at Century's End: Essays on History and Politics</td>
                        <td data-label="Author">Subhash Kak (Author)</td>
                        <td data-label="Publisher">South Asia Books</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">India's Secularism: New Name for National Subversion</td>
                        <td data-label="Author">Sita Ram Goel (Author), Yashpal Sharma (Translator), Sharma Yashpal (Translator)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Indian Muslims - Who are They</td>
                        <td data-label="Author">K S Lal (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Islam vis-a-vis Hindu temples</td>
                        <td data-label="Author">Sita Ram Goel (Author)</td>
                        <td data-label="Publisher">Voice Of India/Aditya Prakashan</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Jammu and Kashmir Dilemma of Accession: a historical analysis and Lesson</td>
                        <td data-label="Author">Radha Rajan (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Jesus Christ an artifice for aggression</td>
                        <td data-label="Author">Sita Ram Goel (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Jihād: The Islamic Doctrine of Permanent War</td>
                        <td data-label="Author">Suhāsa Majumadāra</td>
                        <td data-label="Publisher">South Asia Books</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Jizyah and the spread of Islam</td>
                        <td data-label="Author">Harsh Narain (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Life of Mahomet: From Original Sources</td>
                        <td data-label="Author">Sir William Muir</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Malabar and the Portuguese</td>
                        <td data-label="Author">K. M. Panikkar</td>
                        <td data-label="Publisher">Voice of India (Aditya Prakashan)</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Meditations: Yogas, Gods, Religions</td>
                        <td data-label="Author">Ram Swarup (Author)</td>
                        <td data-label="Publisher">Motilal Banarsidass Publications</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Mohammed and the rise of Islam</td>
                        <td data-label="Author">D. S. Margoliouth (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Muslim league attack on Sikhs and Hindus in the Punjab 1947</td>
                        <td data-label="Author">S. Gurbachan Singh Talib (Author), Ram Swarup (Introduction)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">A Muslim Missionary in Mediaeval Kashmir</td>
                        <td data-label="Author">Kashinath Pandit (Editor)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Muslim Separatism: Causes and Consequences</td>
                        <td data-label="Author">Sita ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Myth of Saint Thomas and the Mylapore Shiva Temple</td>
                        <td data-label="Author">Sharan (Author), Ishwar (Author)</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Myths of composite culture and equality of religions</td>
                        <td data-label="Author">Harsh Narain (Author)</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Nal-Damayanti (नल-दमयन्ती)</td>
                        <td data-label="Author">Sita ram Goel</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Nalkatha (Raghuvansh ke ek prasidh raja Nal ki sankshipt gatha)</td>
                        <td data-label="Author">Bhagvania, Rohtas Simh</td>
                        <td data-label="Publisher">ADITYA PRAKASHAN</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Negationism in India: concealing the record of Islam</td>
                        <td data-label="Author">Koenraad Elst (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">On Hinduism: Reviews and Reflections, Foreword by David Frawley</td>
                        <td data-label="Author">Ram Swarup (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">On Modi Time : Merits And Flaws of Hindu Activism In Its Day Of Incumbency</td>
                        <td data-label="Author">KOENRAAD ELST (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Pandav Priya Panchali (in Hindi)</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Perversion of India's Political Parlance</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Pope John Paul II on Eastern Religions and Yoga: A Hindu-Buddhist Rejoinder</td>
                        <td data-label="Author">Ram Swarup (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Promblem with Secularism</td>
                        <td data-label="Author">Koenraad Elst (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Profiles in Deception: Ayodhya and the Dead Sea Scrolls</td>
                        <td data-label="Author">Navaratna Srinivasa Rajaram (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The prolonged partition and its pogroms: testimonies on violence against Hindus in East Bengal 1946-64</td>
                        <td data-label="Author">A.J. Kamra (Author), Koenraad Elst (Foreword)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Pseudo-Secularism Christian Missions and Hindu Resistance</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Radical universalism: does Hinduism teach that all religions are the same?</td>
                        <td data-label="Author">Frank Morales (Author), foreword by David Frawley</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Road to Ayodhya</td>
                        <td data-label="Author">Jay Dubashi (Author)</td>
                        <td data-label="Publisher">South Asia Books</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Rushdie Affair: The Novel, the Ayatollah, and the West</td>
                        <td data-label="Author">Daniel Pipes</td>
                        <td data-label="Publisher">Routledge</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Saffron Swastika: The Notion of "Hindu Fascism"</td>
                        <td data-label="Author">Koenraad Elst (Author)</td>
                        <td data-label="Publisher">Voice Of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Shrinking Hindu Nation: Behind Every Jinnah There is Always Gandhi</td>
                        <td data-label="Author">Radha Rajan</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Stalinist Historians Spread the Big Lie</td>
                        <td data-label="Author">Sita Ram Goe</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">The Story of Islamic Imperialism in India</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">South Asia Books</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Time for Stock Taking, Whither Sangh Parivar?</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Understanding Islam through Hadis - Religious Faith or Fanaticism?</td>
                        <td data-label="Author">Ram Swarup (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Vedic Aryans and the Origins of Civilization: Forth Expanded Edition with Additions on Natural History, Genetics and the Closing of Aryan Myth</td>
                        <td data-label="Author">David Frawley Navaratna Rajaram (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Tipu Sultan: Villain or Hero?</td>
                        <td data-label="Author">(An anthology)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Vindicated by time the Niyogi committee report on Christian missionary activities</td>
                        <td data-label="Author">Sita Ram Goel (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Who is a Hindu? Hindu Revivalist Views of Animism, Buddhism, Sikhism, and Other Offshoots of Hinduism</td>
                        <td data-label="Author">Koenraad Elst (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Woman in Islam</td>
                        <td data-label="Author">Ram Swarup (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Woman, Church and State: A Historical Account of the Status of Woman Through the Christian Ages; With Reminiscences of the Matriarchate</td>
                        <td data-label="Author">Matilda Joslyn Gage (Author)</td>
                        <td data-label="Publisher">Forgotten Books</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">The Word as Revelation: Names of Gods, Foreword by David Frawley</td>
                        <td data-label="Author">Ram Swarup (Author)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Jai Somnath(जय सोमनाथ)</td>
                        <td data-label="Author">Kanaiyalal Maneklal Munshi</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Nachyo Bahut Gopal(नाच्यौ बहुत गोपाल)</td>
                        <td data-label="Author">Nagar (Author), Amritlal (Author)</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Manas Ka Hans(मानस का हंस)</td>
                        <td data-label="Author">Amritlal Nagar</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Ekda Naimisharanye(एकदा नैमिषारण्य)</td>
                        <td data-label="Author">Amritlal Nagar</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Sahyadri Ki Chattanen (सह्याद्रि की चट्टानें )</td>
                        <td data-label="Author">Acharya Chatursen (Author)</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Somnath (सोमनाथ)</td>
                        <td data-label="Author">Acharya Chatursen</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Shriman Yogi (Marathi) </td>
                        <td data-label="Author">Ranjeet Desai (Author)</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Bharat Mein Parchalit Secularvad (भारत में परचलित सेक्युलरवाद)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Samyavad ke Sau Apradh (सम्यवाद के सौ अपराध)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Marxwad ke khandar (मार्क्सवाद के खण्डर)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Buddhijeeviyon ki Afeem: Samvaad Ek Vivechan (बुद्धिजीवियों की अफ़ीम साम्यवाद: एक विवेचन)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">Bharat Me Marxvad Itihas-Lekhan (भारत में मार्क्सवाद इतिहास-लेखन)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Jihadi Aatankwad (जिहादी आतंकवाद)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>
                    <tr>
                        <td data-label="Book Title">PICHDEN KYON MUSALMAN (पिछड़ें क्यों मुसलमान)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Muslim Soche (मुस्लिम सोचे)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Gandhi Ke Bramhacharya Prayog (गांधी के ब्रह्मचर्य प्रयोग)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Gandhi ahimsa aur rajniti (गांधी अहिंसा और राजनीति)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Shiksha Aur Rajniti (शिक्षा और राजनीति)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Adhyatmik aakraman aur ghar wapsi (आध्यात्मिक आक्रमण और घर वापसी)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Bharat par Karl Marx aur Marxvadi Itihas Lekhan (भारत पर कार्ल मार्क्स और मार्क्सवादी इतिहास लेखन)</td>
                        <td data-label="Author">Shankar Sharan</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Hindu samaj: sankaton ke ghere mein (हिंदू समाज: संकट के घेरे में)</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Secularism: rastra droha ka dusra nam (सेक्युलरिज्म: राष्ट्र द्रोह का दूसरा नाम)</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Bharat mem Islami Samrajyavada ki kahani (भारत पुरुष इस्लामिक साम्राज्यवाद की कहानी)</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Maim Hindu Kaise Bana: Ek Bauddhik Atmakatha (मैं हिंदू कैसे बना: एक बौधिक आत्मकथा)</td>
                        <td data-label="Author">Sita Ram Goel (Author), Shankar Sharan (Translator)</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Shaktiputra Shivaji (शक्तिपुत्र शिवाजी)</td>
                        <td data-label="Author">Sita Ram Goel</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Bharat Ke Islamikaran Ke Char Charan (भारत के इस्लामीकरण के चार चरण)</td>
                        <td data-label="Author">Purushottam Nagesh Oak (पुरूषोत्तम नागेश ओक)</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Muslim Rajnitik Chintan Aur Akanshayen (मुस्लिम राजनितिक चिंतन और आकांक्षाएँ)</td>
                        <td data-label="Author">Purushottam Nagesh Oak (पुरूषोत्तम नागेश ओक)</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Bhartiya Itihas Ki Bhayankar Bhulen (भारतीय इतिहास की भयंकर भूलें)</td>
                        <td data-label="Author">Purushottam Nagesh Oak (पुरूषोत्तम नागेश ओक)</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Bhartiya Musalmano ke Hindu Purvaj (भारतीय मुसलमानों के हिंदू पूर्वज)</td>
                        <td data-label="Author">Purushottam Nagesh Oak (पुरूषोत्तम नागेश ओक)</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Sufiyon dwara Bharat ka Islamikaran (सूफियों द्वारा भारत का इस्लामीकरण)</td>
                        <td data-label="Author">Purushottam Nagesh Oak (पुरूषोत्तम नागेश ओक)</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Hindu Rashtra Ki Avdharna (हिन्दू राष्ट्र की अवधारणा)</td>
                        <td data-label="Author">Abhas Kumar Chatterjee(आभास कुमार चटर्जी)</td>
                        <td data-label="Publisher">suruchi prakashan</td>
                    </tr>
                    
 
                    <tr>
                        <td data-label="Book Title">Hadis ke madhyam se Islam ka adhyayan (हदीस के माध्यम से इस्लाम का अध्ययन)</td>
                        <td data-label="Author">Ram swarup(author), Rameshwar mishra 'pankaj'(Transalator))</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Samskrtik asmita ki pratik: Gomata (सांस्कृतिक अस्मिता की प्रतीक: गोमाता)</td>
                        <td data-label="Author">Rameswar Mishra "Pankaj" (Author)  </td>
                        <td data-label="Publisher">Voice of India </td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Samyak-Sambuddha (सम्यक-सम्बुद्ध)</td>
                        <td data-label="Author">Sita ram goel</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Saptasheel (सप्तशील)</td>
                        <td data-label="Author">Sita ram goel</td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title">Satyakam sokratej (सत्यकाम सोकरतेज)</td>
                        <td data-label="Author">platon(author), Sita ram goel(Translator)</td>
                        <td data-label="Publisher">Voice of India</td>
                    </tr>

                    <tr>
                        <td data-label="Book Title"></td>
                        <td data-label="Author"></td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title"></td>
                        <td data-label="Author"></td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title"></td>
                        <td data-label="Author"></td>
                        <td data-label="Publisher"></td>
                    </tr>

                    <tr>
                        <td data-label="Book Title"></td>
                        <td data-label="Author"></td>
                        <td data-label="Publisher"></td>
                    </tr>




                    <!-- Add more rows as needed -->
                </tbody>
            </table>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script>
        $(document).ready(function() {
            // Initialize the tablesorter plugin
            $("#myTable").tablesorter();
        });
    </script>
</body>
</html>
